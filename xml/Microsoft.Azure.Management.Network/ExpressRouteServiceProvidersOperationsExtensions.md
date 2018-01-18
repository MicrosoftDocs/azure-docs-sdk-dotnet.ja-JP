<Type Name="ExpressRouteServiceProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteServiceProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteServiceProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="55f3e-101">ExpressRouteServiceProvidersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="55f3e-101">Extension methods for ExpressRouteServiceProvidersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt; List (this Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt; List(class Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.List(Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IExpressRouteServiceProvidersOperations) As IPage(Of ExpressRouteServiceProvider)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55f3e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55f3e-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55f3e-103">使用可能なすべての express route サービス プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="55f3e-103">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55f3e-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55f3e-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55f3e-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55f3e-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55f3e-106">使用可能なすべての express route サービス プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="55f3e-106">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt; ListNext (this Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt; ListNext(class Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IExpressRouteServiceProvidersOperations, nextPageLink As String) As IPage(Of ExpressRouteServiceProvider)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55f3e-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55f3e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="55f3e-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="55f3e-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55f3e-109">使用可能なすべての express route サービス プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="55f3e-109">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteServiceProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteServiceProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteServiceProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="55f3e-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="55f3e-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="55f3e-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="55f3e-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="55f3e-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="55f3e-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="55f3e-113">使用可能なすべての express route サービス プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="55f3e-113">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>