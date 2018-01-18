<Type Name="OperationsExtensions" FullName="Microsoft.Azure.Management.Network.OperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.OperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationsExtensions" />
  <TypeSignature Language="F#" Value="type OperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9807-101">操作の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f9807-101">Extension methods for Operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt; List (this Microsoft.Azure.Management.Network.IOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Operation&gt; List(class Microsoft.Azure.Management.Network.IOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.OperationsExtensions.List(Microsoft.Azure.Management.Network.IOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IOperations) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;" Usage="Microsoft.Azure.Management.Network.OperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9807-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9807-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9807-103">すべての利用可能なネットワーク Rest API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f9807-103">Lists all of the available Network Rest API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Operation&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.OperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.Network.OperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.OperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9807-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9807-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9807-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9807-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9807-106">すべての利用可能なネットワーク Rest API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f9807-106">Lists all of the available Network Rest API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt; ListNext (this Microsoft.Azure.Management.Network.IOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Operation&gt; ListNext(class Microsoft.Azure.Management.Network.IOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.OperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IOperations, nextPageLink As String) As IPage(Of Operation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;" Usage="Microsoft.Azure.Management.Network.OperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9807-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9807-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9807-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9807-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9807-109">すべての利用可能なネットワーク Rest API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f9807-109">Lists all of the available Network Rest API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.Operation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.OperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.Network.OperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.OperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9807-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9807-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9807-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9807-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9807-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9807-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9807-113">すべての利用可能なネットワーク Rest API 操作の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="f9807-113">Lists all of the available Network Rest API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>