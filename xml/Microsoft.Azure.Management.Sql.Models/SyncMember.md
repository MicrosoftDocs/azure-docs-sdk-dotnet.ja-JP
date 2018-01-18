<Type Name="SyncMember" FullName="Microsoft.Azure.Management.Sql.Models.SyncMember">
  <TypeSignature Language="C#" Value="public class SyncMember : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncMember extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncMember" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncMember&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type SyncMember = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="da185-101">Azure SQL データベースの同期メンバーの場合は。</span><span class="sxs-lookup"><span data-stu-id="da185-101">An Azure SQL Database sync member.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMember ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncMember.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="da185-102">SyncMember クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="da185-102">Initializes a new instance of the SyncMember class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncMember (string id = null, string name = null, string type = null, string databaseType = null, string syncAgentId = null, Nullable&lt;Guid&gt; sqlServerDatabaseId = null, string serverName = null, string databaseName = null, string userName = null, string password = null, string syncDirection = null, string syncState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string databaseType, string syncAgentId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; sqlServerDatabaseId, string serverName, string databaseName, string userName, string password, string syncDirection, string syncState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncMember.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional databaseType As String = null, Optional syncAgentId As String = null, Optional sqlServerDatabaseId As Nullable(Of Guid) = null, Optional serverName As String = null, Optional databaseName As String = null, Optional userName As String = null, Optional password As String = null, Optional syncDirection As String = null, Optional syncState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncMember : string * string * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncMember" Usage="new Microsoft.Azure.Management.Sql.Models.SyncMember (id, name, type, databaseType, syncAgentId, sqlServerDatabaseId, serverName, databaseName, userName, password, syncDirection, syncState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="databaseType" Type="System.String" />
        <Parameter Name="syncAgentId" Type="System.String" />
        <Parameter Name="sqlServerDatabaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="syncDirection" Type="System.String" />
        <Parameter Name="syncState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="da185-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="da185-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="da185-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="da185-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="da185-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="da185-105">Resource type.</span></span></param>
        <param name="databaseType"><span data-ttu-id="da185-106">同期メンバー データベースの種類。</span><span class="sxs-lookup"><span data-stu-id="da185-106">Database type of the sync member.</span></span>
            <span data-ttu-id="da185-107">使用可能な値が含まれます: 'AzureSqlDatabase'、'SqlServerDatabase'</span><span class="sxs-lookup"><span data-stu-id="da185-107">Possible values include: 'AzureSqlDatabase', 'SqlServerDatabase'</span></span></param>
        <param name="syncAgentId"><span data-ttu-id="da185-108">同期のメンバーで同期エージェントの ARM リソース id です。</span><span class="sxs-lookup"><span data-stu-id="da185-108">ARM resource id of the sync agent in the sync member.</span></span></param>
        <param name="sqlServerDatabaseId"><span data-ttu-id="da185-109">同期のメンバーの SQL Server データベースの id。</span><span class="sxs-lookup"><span data-stu-id="da185-109">SQL Server database id of the sync member.</span></span></param>
        <param name="serverName"><span data-ttu-id="da185-110">同期のメンバーでは、メンバー データベースのサーバー名</span><span class="sxs-lookup"><span data-stu-id="da185-110">Server name of the member database in the sync member</span></span></param>
        <param name="databaseName"><span data-ttu-id="da185-111">同期のメンバーでは、メンバー データベースのデータベース名。</span><span class="sxs-lookup"><span data-stu-id="da185-111">Database name of the member database in the sync member.</span></span></param>
        <param name="userName"><span data-ttu-id="da185-112">同期のメンバーでは、メンバー データベースのユーザー名。</span><span class="sxs-lookup"><span data-stu-id="da185-112">User name of the member database in the sync member.</span></span></param>
        <param name="password"><span data-ttu-id="da185-113">同期のメンバーでは、メンバー データベースのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="da185-113">Password of the member database in the sync member.</span></span></param>
        <param name="syncDirection"><span data-ttu-id="da185-114">同期のメンバーの同期の方向。</span><span class="sxs-lookup"><span data-stu-id="da185-114">Sync direction of the sync member.</span></span>
            <span data-ttu-id="da185-115">使用可能な値が含まれます '双方向'、'OneWayMemberToHub'、'OneWayHubToMember'。</span><span class="sxs-lookup"><span data-stu-id="da185-115">Possible values include: 'Bidirectional', 'OneWayMemberToHub', 'OneWayHubToMember'</span></span></param>
        <param name="syncState"><span data-ttu-id="da185-116">同期メンバの状態を同期します。</span><span class="sxs-lookup"><span data-stu-id="da185-116">Sync state of the sync member.</span></span> <span data-ttu-id="da185-117">使用可能な値が含まれます: 'SyncInProgress'、'SyncSucceeded'、'SyncFailed'、'DisabledTombstoneCleanup'、'DisabledBackupRestore'、'SyncSucceededWithWarnings'、'SyncCancelling'、'SyncCancelled'、'UnProvisioned'、'プロビジョニング中'、'準備済み''ProvisionFailed'、'プロビジョニング解除'、' プロビジョニングが解除された '、'DeProvisionFailed'、'再プロビジョニング'、'ReprovisionFailed'、'UnReprovisioned'</span><span class="sxs-lookup"><span data-stu-id="da185-117">Possible values include: 'SyncInProgress', 'SyncSucceeded', 'SyncFailed', 'DisabledTombstoneCleanup', 'DisabledBackupRestore', 'SyncSucceededWithWarnings', 'SyncCancelling', 'SyncCancelled', 'UnProvisioned', 'Provisioning', 'Provisioned', 'ProvisionFailed', 'DeProvisioning', 'DeProvisioned', 'DeProvisionFailed', 'Reprovisioning', 'ReprovisionFailed', 'UnReprovisioned'</span></span></param>
        <summary>
            <span data-ttu-id="da185-118">SyncMember クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="da185-118">Initializes a new instance of the SyncMember class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-119">取得または同期のメンバーでは、メンバー データベースのデータベース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-119">Gets or sets database name of the member database in the sync member.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseType">
      <MemberSignature Language="C#" Value="public string DatabaseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.DatabaseType" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseType As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseType : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.DatabaseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-120">取得または設定の同期メンバー データベースの種類。</span><span class="sxs-lookup"><span data-stu-id="da185-120">Gets or sets database type of the sync member.</span></span> <span data-ttu-id="da185-121">使用可能な値が含まれます: 'AzureSqlDatabase'、'SqlServerDatabase'</span><span class="sxs-lookup"><span data-stu-id="da185-121">Possible values include: 'AzureSqlDatabase', 'SqlServerDatabase'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-122">取得または同期のメンバーでは、メンバー データベースのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-122">Gets or sets password of the member database in the sync member.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-123">取得または同期のメンバーでは、メンバー データベースのサーバー名を設定</span><span class="sxs-lookup"><span data-stu-id="da185-123">Gets or sets server name of the member database in the sync member</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerDatabaseId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; SqlServerDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; SqlServerDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.SqlServerDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlServerDatabaseId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.SqlServerDatabaseId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.SqlServerDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sqlServerDatabaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-124">取得または同期メンバーの SQL Server データベースの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-124">Gets or sets SQL Server database id of the sync member.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncAgentId">
      <MemberSignature Language="C#" Value="public string SyncAgentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncAgentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.SyncAgentId" />
      <MemberSignature Language="VB.NET" Value="Public Property SyncAgentId As String" />
      <MemberSignature Language="F#" Value="member this.SyncAgentId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.SyncAgentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.syncAgentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-125">取得または同期エージェントの ARM リソース id を同期メンバーに設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-125">Gets or sets ARM resource id of the sync agent in the sync member.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncDirection">
      <MemberSignature Language="C#" Value="public string SyncDirection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncDirection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.SyncDirection" />
      <MemberSignature Language="VB.NET" Value="Public Property SyncDirection As String" />
      <MemberSignature Language="F#" Value="member this.SyncDirection : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.SyncDirection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.syncDirection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-126">取得または同期メンバーの同期の方向を設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-126">Gets or sets sync direction of the sync member.</span></span> <span data-ttu-id="da185-127">使用可能な値が含まれます '双方向'、'OneWayMemberToHub'、'OneWayHubToMember'。</span><span class="sxs-lookup"><span data-stu-id="da185-127">Possible values include: 'Bidirectional', 'OneWayMemberToHub', 'OneWayHubToMember'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncState">
      <MemberSignature Language="C#" Value="public string SyncState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.SyncState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncState As String" />
      <MemberSignature Language="F#" Value="member this.SyncState : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.SyncState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.syncState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-128">取得では、同期メンバの状態を同期します。</span><span class="sxs-lookup"><span data-stu-id="da185-128">Gets sync state of the sync member.</span></span> <span data-ttu-id="da185-129">使用可能な値が含まれます: 'SyncInProgress'、'SyncSucceeded'、'SyncFailed'、'DisabledTombstoneCleanup'、'DisabledBackupRestore'、'SyncSucceededWithWarnings'、'SyncCancelling'、'SyncCancelled'、'UnProvisioned'、'プロビジョニング中'、'準備済み''ProvisionFailed'、'プロビジョニング解除'、' プロビジョニングが解除された '、'DeProvisionFailed'、'再プロビジョニング'、'ReprovisionFailed'、'UnReprovisioned'</span><span class="sxs-lookup"><span data-stu-id="da185-129">Possible values include: 'SyncInProgress', 'SyncSucceeded', 'SyncFailed', 'DisabledTombstoneCleanup', 'DisabledBackupRestore', 'SyncSucceededWithWarnings', 'SyncCancelling', 'SyncCancelled', 'UnProvisioned', 'Provisioning', 'Provisioned', 'ProvisionFailed', 'DeProvisioning', 'DeProvisioned', 'DeProvisionFailed', 'Reprovisioning', 'ReprovisionFailed', 'UnReprovisioned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncMember.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncMember.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="da185-130">取得または同期のメンバーでは、メンバー データベースのユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="da185-130">Gets or sets user name of the member database in the sync member.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>