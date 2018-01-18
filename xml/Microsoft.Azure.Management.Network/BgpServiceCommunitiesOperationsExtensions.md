<Type Name="BgpServiceCommunitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BgpServiceCommunitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BgpServiceCommunitiesOperationsExtensions = class" />
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
            <span data-ttu-id="0a960-101">BgpServiceCommunitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0a960-101">Extension methods for BgpServiceCommunitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt; List (this Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt; List(class Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.List(Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBgpServiceCommunitiesOperations) As IPage(Of BgpServiceCommunity)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;" Usage="Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a960-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a960-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a960-103">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a960-103">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a960-104">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a960-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a960-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a960-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a960-106">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a960-106">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt; ListNext (this Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt; ListNext(class Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBgpServiceCommunitiesOperations, nextPageLink As String) As IPage(Of BgpServiceCommunity)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;" Usage="Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a960-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a960-107">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0a960-108">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0a960-108">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a960-109">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a960-109">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.BgpServiceCommunitiesOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BgpServiceCommunity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a960-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a960-110">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0a960-111">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0a960-111">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a960-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a960-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a960-113">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a960-113">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>