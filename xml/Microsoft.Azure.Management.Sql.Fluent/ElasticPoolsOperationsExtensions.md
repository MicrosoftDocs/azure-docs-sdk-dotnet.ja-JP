<Type Name="ElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f21b-101">ElasticPoolsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9f21b-101">Extension methods for ElasticPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-105">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-106">処理するには、Azure SQL 弾力性プールの名前 (更新または作成) します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-106">The name of the Azure SQL Elastic Pool to be operated on (Updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9f21b-107">作成または弾力性プールの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-107">The required parameters for creating or updating an Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-109">新しい Azure SQL 弾力性プールを作成するか、既存の Azure SQL 弾力性プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-109">Creates a new Azure SQL elastic pool or updates an existing Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, elasticPoolName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-111">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-112">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-113">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-113">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-114">処理するには、Azure SQL 弾力性プールの名前 (更新または作成) します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-114">The name of the Azure SQL Elastic Pool to be operated on (Updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9f21b-115">作成または弾力性プールの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-115">The required parameters for creating or updating an Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-117">新しい Azure SQL 弾力性プールを作成するか、既存の Azure SQL 弾力性プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-117">Creates a new Azure SQL elastic pool or updates an existing Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-119">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-119">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-120">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-120">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-121">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-121">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-122">削除するには、Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-122">The name of the Azure SQL Elastic Pool to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-124">Azure SQL 弾力性プールを削除します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-124">Deletes the Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt; GetAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-126">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-127">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-128">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-128">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-129">取得するには、Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-129">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-131">Azure SQL 弾力性プールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-131">Gets information about an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt; GetDatabaseAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabaseAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.GetDatabaseAsync (operations, resourceGroupName, serverName, elasticPoolName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;GetDatabaseAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-135">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-135">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-136">取得するには、Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-136">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9f21b-137">取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-137">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-139">Azure SQL 弾力性プール内で Azure SQL データベースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-139">Gets information about an Azure SQL database inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt; ListActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListActivityAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-141">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-141">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-142">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-142">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-143">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-143">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-144">現在のアクティビティを取得する対象の Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-144">The name of the Azure SQL Elastic Pool for which to get the current activity.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-146">Azure SQL 弾力性プールのアクティビティに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-146">Returns information about Azure SQL elastic pool activities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-148">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-148">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-149">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-149">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-150">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-150">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-152">Azure SQL 弾力性プールに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-152">Returns information about Azure SQL elastic pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabaseActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt; ListDatabaseActivityAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabaseActivityAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabaseActivityAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabaseActivityAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolDatabaseActivityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-154">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-155">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-156">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-156">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-157">Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-157">The name of the Azure SQL Elastic Pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-159">Azure SQL 弾力性プール内での Azure SQL データベースの利用状況に関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-159">Returns information about activity on Azure SQL databases inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations operations, string resourceGroupName, string serverName, string elasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions.ListDatabasesAsync (operations, resourceGroupName, serverName, elasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ElasticPoolsOperationsExtensions/&lt;ListDatabasesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9f21b-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9f21b-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9f21b-161">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-161">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9f21b-162">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9f21b-162">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9f21b-163">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-163">The name of the Azure SQL server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="9f21b-164">取得するには、Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9f21b-164">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9f21b-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9f21b-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9f21b-166">Azure SQL 弾力性プール内での Azure SQL データベースに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9f21b-166">Returns information about an Azure SQL database inside of an Azure SQL elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>