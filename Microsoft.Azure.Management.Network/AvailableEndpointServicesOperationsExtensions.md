<Type Name="AvailableEndpointServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AvailableEndpointServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AvailableEndpointServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AvailableEndpointServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AvailableEndpointServicesOperationsExtensions = class" />
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
            <span data-ttu-id="4be01-101">AvailableEndpointServicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4be01-101">Extension methods for AvailableEndpointServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt; List (this Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt; List(class Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.List(Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAvailableEndpointServicesOperations, location As String) As IPage(Of EndpointServiceResult)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;" Usage="Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.List (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4be01-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4be01-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4be01-103">使用可能なエンドポイント サービスを確認する場所です。</span><span class="sxs-lookup"><span data-stu-id="4be01-103">The location to check available endpoint services.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4be01-104">使用可能なエンドポイント サービスの値を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4be01-104">List what values of endpoint services are available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt;" Usage="Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4be01-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4be01-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4be01-106">使用可能なエンドポイント サービスを確認する場所です。</span><span class="sxs-lookup"><span data-stu-id="4be01-106">The location to check available endpoint services.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4be01-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4be01-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4be01-108">使用可能なエンドポイント サービスの値を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4be01-108">List what values of endpoint services are available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt; ListNext (this Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt; ListNext(class Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAvailableEndpointServicesOperations, nextPageLink As String) As IPage(Of EndpointServiceResult)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;" Usage="Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4be01-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4be01-109">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4be01-110">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4be01-110">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4be01-111">使用可能なエンドポイント サービスの値を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4be01-111">List what values of endpoint services are available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt;" Usage="Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.AvailableEndpointServicesOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.EndpointServiceResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IAvailableEndpointServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4be01-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4be01-112">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4be01-113">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4be01-113">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4be01-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4be01-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4be01-115">使用可能なエンドポイント サービスの値を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4be01-115">List what values of endpoint services are available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>