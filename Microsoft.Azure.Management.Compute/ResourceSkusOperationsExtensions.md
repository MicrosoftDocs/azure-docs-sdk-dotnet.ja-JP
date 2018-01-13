<Type Name="ResourceSkusOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceSkusOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceSkusOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceSkusOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceSkusOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25f80-101">ResourceSkusOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="25f80-101">Extension methods for ResourceSkusOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt; List (this Microsoft.Azure.Management.Compute.IResourceSkusOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSku&gt; List(class Microsoft.Azure.Management.Compute.IResourceSkusOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.List(Microsoft.Azure.Management.Compute.IResourceSkusOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourceSkusOperations) As IPage(Of ResourceSku)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IResourceSkusOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;" Usage="Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IResourceSkusOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="25f80-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="25f80-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="25f80-103">サブスクリプションの利用可能な Microsoft.Compute Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="25f80-103">Gets the list of Microsoft.Compute SKUs available for your Subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IResourceSkusOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IResourceSkusOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IResourceSkusOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="25f80-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="25f80-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="25f80-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="25f80-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="25f80-106">サブスクリプションの利用可能な Microsoft.Compute Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="25f80-106">Gets the list of Microsoft.Compute SKUs available for your Subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt; ListNext (this Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSku&gt; ListNext(class Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IResourceSkusOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourceSkusOperations, nextPageLink As String) As IPage(Of ResourceSku)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IResourceSkusOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;" Usage="Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IResourceSkusOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="25f80-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="25f80-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="25f80-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="25f80-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="25f80-109">サブスクリプションの利用可能な Microsoft.Compute Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="25f80-109">Gets the list of Microsoft.Compute SKUs available for your Subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IResourceSkusOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IResourceSkusOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IResourceSkusOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ResourceSkusOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ResourceSku&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IResourceSkusOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="25f80-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="25f80-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="25f80-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="25f80-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="25f80-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="25f80-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="25f80-113">サブスクリプションの利用可能な Microsoft.Compute Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="25f80-113">Gets the list of Microsoft.Compute SKUs available for your Subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>