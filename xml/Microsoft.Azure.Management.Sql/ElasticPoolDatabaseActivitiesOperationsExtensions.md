<Type Name="ElasticPoolDatabaseActivitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolDatabaseActivitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolDatabaseActivitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolDatabaseActivitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolDatabaseActivitiesOperationsExtensions = class" />
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
            <span data-ttu-id="e04f1-101">ElasticPoolDatabaseActivitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e04f1-101">Extension methods for ElasticPoolDatabaseActivitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByElasticPool">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt; ListByElasticPool (this Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt; ListByElasticPool(class Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions.ListByElasticPool(Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByElasticPool (operations As IElasticPoolDatabaseActivitiesOperations, resourceGroupName As String, serverName As String, elasticPoolName As String) As IEnumerable(Of ElasticPoolDatabaseActivity)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPool : Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions.ListByElasticPool (operations, resourceGroupName, serverName, elasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e04f1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e04f1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e04f1-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e04f1-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="e04f1-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e04f1-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-105">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="e04f1-106">弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-106">The name of the elastic pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e04f1-107">エラスティック プール内のデータベースのアクティビティを返します。</span><span class="sxs-lookup"><span data-stu-id="e04f1-107">Returns activity on databases inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt; ListByElasticPoolAsync (this Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt; ListByElasticPoolAsync(class Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions.ListByElasticPoolAsync(Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByElasticPoolAsync : Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions.ListByElasticPoolAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ElasticPoolDatabaseActivitiesOperationsExtensions/&lt;ListByElasticPoolAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e04f1-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e04f1-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e04f1-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e04f1-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="e04f1-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e04f1-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-111">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="e04f1-112">弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="e04f1-112">The name of the elastic pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e04f1-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e04f1-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e04f1-114">エラスティック プール内のデータベースのアクティビティを返します。</span><span class="sxs-lookup"><span data-stu-id="e04f1-114">Returns activity on databases inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>