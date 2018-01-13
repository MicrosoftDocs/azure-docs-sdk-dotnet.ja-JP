<Type Name="UsagesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsagesOperationsExtensions = class" />
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
            <span data-ttu-id="2a93e-101">UsagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2a93e-101">Extension methods for UsagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IUsagesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IUsagesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IUsagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IUsagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IUsagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a93e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2a93e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2a93e-103">リソースの利用状況クエリが実行する場所です。</span><span class="sxs-lookup"><span data-stu-id="2a93e-103">The location where resource usage is queried.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2a93e-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2a93e-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a93e-105">リストは、サブスクリプションの使用法を計算します。</span><span class="sxs-lookup"><span data-stu-id="2a93e-105">Lists compute usages for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IUsagesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IUsagesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IUsagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IUsagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.UsagesOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IUsagesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2a93e-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2a93e-106">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2a93e-107">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2a93e-107">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2a93e-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2a93e-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2a93e-109">リストは、サブスクリプションの使用法を計算します。</span><span class="sxs-lookup"><span data-stu-id="2a93e-109">Lists compute usages for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>