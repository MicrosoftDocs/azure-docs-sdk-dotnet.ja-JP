<Type Name="ElasticPoolActivitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolActivitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolActivitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolActivitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2e16-101">ElasticPoolActivitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a2e16-101">Extension methods for ElasticPoolActivitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByElasticPool">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt; ListByElasticPool (this Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt; ListByElasticPool(class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPool(Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByElasticPool (operations As IElasticPoolActivitiesOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of ElasticPoolActivity)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPool : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPool (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2e16-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2e16-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2e16-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2e16-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2e16-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2e16-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-105">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a2e16-106">現在のアクティビティを取得する対象の弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-106">The name of the elastic pool for which to get the current activity.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2e16-107">エラスティック プールのアクティビティを返します。</span><span class="sxs-lookup"><span data-stu-id="a2e16-107">Returns elastic pool activities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt; ListByElasticPoolAsync (this Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt; ListByElasticPoolAsync(class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPoolAsync(Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPoolAsync : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions.ListByElasticPoolAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolActivitiesOperationsExtensions/&lt;ListByElasticPoolAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2e16-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2e16-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2e16-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2e16-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2e16-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2e16-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-111">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="a2e16-112">現在のアクティビティを取得する対象の弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="a2e16-112">The name of the elastic pool for which to get the current activity.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2e16-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2e16-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2e16-114">エラスティック プールのアクティビティを返します。</span><span class="sxs-lookup"><span data-stu-id="a2e16-114">Returns elastic pool activities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>