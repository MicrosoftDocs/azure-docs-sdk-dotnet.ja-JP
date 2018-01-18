<Type Name="SubscriptionDefinitionsOperationMetadataOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionDefinitionsOperationMetadataOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionDefinitionsOperationMetadataOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionDefinitionsOperationMetadataOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsOperationMetadataOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="40fc3-101">SubscriptionDefinitionsOperationMetadataOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="40fc3-101">Extension methods for SubscriptionDefinitionsOperationMetadataOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt; List (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Operation&gt; List(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubscriptionDefinitionsOperationMetadataOperations) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="40fc3-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="40fc3-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="40fc3-103">すべての利用可能な Microsoft.Subscription API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="40fc3-103">Lists all of the available Microsoft.Subscription API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="40fc3-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="40fc3-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="40fc3-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="40fc3-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="40fc3-106">すべての利用可能な Microsoft.Subscription API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="40fc3-106">Lists all of the available Microsoft.Subscription API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Operation&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubscriptionDefinitionsOperationMetadataOperations, nextPageLink As String) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="40fc3-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="40fc3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="40fc3-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="40fc3-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="40fc3-109">すべての利用可能な Microsoft.Subscription API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="40fc3-109">Lists all of the available Microsoft.Subscription API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationMetadataOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperationMetadataOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="40fc3-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="40fc3-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="40fc3-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="40fc3-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="40fc3-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="40fc3-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="40fc3-113">すべての利用可能な Microsoft.Subscription API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="40fc3-113">Lists all of the available Microsoft.Subscription API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>