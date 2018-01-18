<Type Name="GeoBackupPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeoBackupPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeoBackupPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GeoBackupPoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="33fb0-101">GeoBackupPoliciesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="33fb0-101">Extension methods for GeoBackupPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As GeoBackupPolicy) As GeoBackupPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-106">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-106">The name of the database.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="33fb0-107">作成または geo バックアップ ポリシーの更新の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="33fb0-107">The required parameters for creating or updating the geo backup policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-108">データベースの地理的バックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-108">Updates a database geo backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-113">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-113">The name of the database.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="33fb0-114">作成または geo バックアップ ポリシーの更新の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="33fb0-114">The required parameters for creating or updating the geo backup policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33fb0-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33fb0-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-116">データベースの地理的バックアップ ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-116">Updates a database geo backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy Get (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy Get(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As GeoBackupPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-121">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-121">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-122">Geo バックアップ ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-122">Gets a geo backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-127">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-127">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33fb0-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33fb0-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-129">Geo バックアップ ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-129">Gets a geo backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IGeoBackupPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of GeoBackupPolicy)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-133">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-133">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-134">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-134">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-135">バックアップ ポリシーの地域の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-135">Returns a list of geo backup policies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.GeoBackupPoliciesOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="33fb0-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="33fb0-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="33fb0-137">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="33fb0-138">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="33fb0-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="33fb0-139">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-139">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="33fb0-140">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="33fb0-140">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33fb0-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33fb0-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33fb0-142">バックアップ ポリシーの地域の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="33fb0-142">Returns a list of geo backup policies.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>