<Type Name="BgpServiceCommunitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BgpServiceCommunitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BgpServiceCommunitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BgpServiceCommunitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b4b2-101">BgpServiceCommunitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-101">Extension methods for BgpServiceCommunitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b4b2-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b4b2-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b4b2-104">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-104">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.BgpServiceCommunitiesOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpServiceCommunityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IBgpServiceCommunitiesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b4b2-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-105">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8b4b2-106">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-106">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8b4b2-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b4b2-108">使用可能なすべての bgp サービス コミュニティを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b4b2-108">Gets all the available bgp service communities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>