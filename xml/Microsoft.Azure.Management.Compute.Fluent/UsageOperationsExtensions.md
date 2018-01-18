<Type Name="UsageOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e4507-101">UsageOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e4507-101">Extension methods for UsageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IUsageOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IUsageOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IUsageOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IUsageOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IUsageOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4507-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e4507-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="e4507-103">リソースの使用状況を照会する場所です。</span><span class="sxs-lookup"><span data-stu-id="e4507-103">The location for which resource usage is queried.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4507-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e4507-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4507-105">サブスクリプションの下のコンピューティング リソースの制限だけでなく、指定した位置、現在のコンピューティング リソースの使用状況情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4507-105">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IUsageOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IUsageOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IUsageOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IUsageOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.UsageOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IUsageOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4507-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e4507-106">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4507-107">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e4507-107">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4507-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e4507-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4507-109">サブスクリプションの下のコンピューティング リソースの制限だけでなく、指定した位置、現在のコンピューティング リソースの使用状況情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="e4507-109">Gets, for the specified location, the current compute resource usage information as well as the limits for compute resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>