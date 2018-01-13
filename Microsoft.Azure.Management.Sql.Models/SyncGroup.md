<Type Name="SyncGroup" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroup">
  <TypeSignature Language="C#" Value="public class SyncGroup : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroup extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroup&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type SyncGroup = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="731b3-101">Azure SQL データベースの同期グループの場合は。</span><span class="sxs-lookup"><span data-stu-id="731b3-101">An Azure SQL Database sync group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="731b3-102">SyncGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="731b3-102">Initializes a new instance of the SyncGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroup (string id = null, string name = null, string type = null, Nullable&lt;int&gt; interval = null, Nullable&lt;DateTime&gt; lastSyncTime = null, string conflictResolutionPolicy = null, string syncDatabaseId = null, string hubDatabaseUserName = null, string hubDatabasePassword = null, string syncState = null, Microsoft.Azure.Management.Sql.Models.SyncGroupSchema schema = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastSyncTime, string conflictResolutionPolicy, string syncDatabaseId, string hubDatabaseUserName, string hubDatabasePassword, string syncState, class Microsoft.Azure.Management.Sql.Models.SyncGroupSchema schema) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroup.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroupSchema)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional interval As Nullable(Of Integer) = null, Optional lastSyncTime As Nullable(Of DateTime) = null, Optional conflictResolutionPolicy As String = null, Optional syncDatabaseId As String = null, Optional hubDatabaseUserName As String = null, Optional hubDatabasePassword As String = null, Optional syncState As String = null, Optional schema As SyncGroupSchema = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroup : string * string * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroupSchema -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroup" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroup (id, name, type, interval, lastSyncTime, conflictResolutionPolicy, syncDatabaseId, hubDatabaseUserName, hubDatabasePassword, syncState, schema)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="lastSyncTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="conflictResolutionPolicy" Type="System.String" />
        <Parameter Name="syncDatabaseId" Type="System.String" />
        <Parameter Name="hubDatabaseUserName" Type="System.String" />
        <Parameter Name="hubDatabasePassword" Type="System.String" />
        <Parameter Name="syncState" Type="System.String" />
        <Parameter Name="schema" Type="Microsoft.Azure.Management.Sql.Models.SyncGroupSchema" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="731b3-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="731b3-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="731b3-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="731b3-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="731b3-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="731b3-105">Resource type.</span></span></param>
        <param name="interval"><span data-ttu-id="731b3-106">同期グループの同期の間隔です。</span><span class="sxs-lookup"><span data-stu-id="731b3-106">Sync interval of the sync group.</span></span></param>
        <param name="lastSyncTime"><span data-ttu-id="731b3-107">同期グループの最後の同期の時刻。</span><span class="sxs-lookup"><span data-stu-id="731b3-107">Last sync time of the sync group.</span></span></param>
        <param name="conflictResolutionPolicy"><span data-ttu-id="731b3-108">同期グループの競合解決ポリシー。</span><span class="sxs-lookup"><span data-stu-id="731b3-108">Conflict resolution policy of the sync group.</span></span> <span data-ttu-id="731b3-109">使用可能な値が含まれます: 'HubWin'、'MemberWin'</span><span class="sxs-lookup"><span data-stu-id="731b3-109">Possible values include: 'HubWin', 'MemberWin'</span></span></param>
        <param name="syncDatabaseId"><span data-ttu-id="731b3-110">同期グループで、sync データベースの ARM リソース id です。</span><span class="sxs-lookup"><span data-stu-id="731b3-110">ARM resource id of the sync database in the sync group.</span></span></param>
        <param name="hubDatabaseUserName"><span data-ttu-id="731b3-111">同期グループ ハブ データベースの資格情報のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="731b3-111">User name for the sync group hub database credential.</span></span></param>
        <param name="hubDatabasePassword"><span data-ttu-id="731b3-112">同期グループ ハブ データベースの資格情報のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="731b3-112">Password for the sync group hub database credential.</span></span></param>
        <param name="syncState"><span data-ttu-id="731b3-113">同期グループの状態を同期します。</span><span class="sxs-lookup"><span data-stu-id="731b3-113">Sync state of the sync group.</span></span> <span data-ttu-id="731b3-114">使用可能な値が含まれます: '準備不完了'、'Error'、'警告'、'進行'、'良い'</span><span class="sxs-lookup"><span data-stu-id="731b3-114">Possible values include: 'NotReady', 'Error', 'Warning', 'Progressing', 'Good'</span></span></param>
        <param name="schema"><span data-ttu-id="731b3-115">同期グループの同期スキーマです。</span><span class="sxs-lookup"><span data-stu-id="731b3-115">Sync schema of the sync group.</span></span></param>
        <summary>
            <span data-ttu-id="731b3-116">SyncGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="731b3-116">Initializes a new instance of the SyncGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictResolutionPolicy">
      <MemberSignature Language="C#" Value="public string ConflictResolutionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictResolutionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.ConflictResolutionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property ConflictResolutionPolicy As String" />
      <MemberSignature Language="F#" Value="member this.ConflictResolutionPolicy : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.ConflictResolutionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.conflictResolutionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-117">取得または同期グループの競合解決ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-117">Gets or sets conflict resolution policy of the sync group.</span></span> <span data-ttu-id="731b3-118">使用可能な値が含まれます: 'HubWin'、'MemberWin'</span><span class="sxs-lookup"><span data-stu-id="731b3-118">Possible values include: 'HubWin', 'MemberWin'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubDatabasePassword">
      <MemberSignature Language="C#" Value="public string HubDatabasePassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubDatabasePassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.HubDatabasePassword" />
      <MemberSignature Language="VB.NET" Value="Public Property HubDatabasePassword As String" />
      <MemberSignature Language="F#" Value="member this.HubDatabasePassword : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.HubDatabasePassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hubDatabasePassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-119">取得または同期グループ ハブ データベースの資格情報のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-119">Gets or sets password for the sync group hub database credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubDatabaseUserName">
      <MemberSignature Language="C#" Value="public string HubDatabaseUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HubDatabaseUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.HubDatabaseUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property HubDatabaseUserName As String" />
      <MemberSignature Language="F#" Value="member this.HubDatabaseUserName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.HubDatabaseUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hubDatabaseUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-120">取得または同期グループ ハブ データベースの資格情報のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-120">Gets or sets user name for the sync group hub database credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-121">取得または同期グループの同期の間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-121">Gets or sets sync interval of the sync group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSyncTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastSyncTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastSyncTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.LastSyncTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSyncTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastSyncTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.LastSyncTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastSyncTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-122">同期グループの最後の同期の時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="731b3-122">Gets last sync time of the sync group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.SyncGroupSchema Schema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.SyncGroupSchema Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.Schema" />
      <MemberSignature Language="VB.NET" Value="Public Property Schema As SyncGroupSchema" />
      <MemberSignature Language="F#" Value="member this.Schema : Microsoft.Azure.Management.Sql.Models.SyncGroupSchema with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SyncGroupSchema</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-123">取得または同期グループの同期のスキーマを設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-123">Gets or sets sync schema of the sync group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncDatabaseId">
      <MemberSignature Language="C#" Value="public string SyncDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.SyncDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SyncDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SyncDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.SyncDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.syncDatabaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="731b3-124">取得または同期グループで、sync データベースの ARM リソース id を設定します。</span><span class="sxs-lookup"><span data-stu-id="731b3-124">Gets or sets ARM resource id of the sync database in the sync group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncState">
      <MemberSignature Language="C#" Value="public string SyncState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroup.SyncState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncState As String" />
      <MemberSignature Language="F#" Value="member this.SyncState : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroup.SyncState" />
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
            <span data-ttu-id="731b3-125">取得では、同期グループの状態を同期します。</span><span class="sxs-lookup"><span data-stu-id="731b3-125">Gets sync state of the sync group.</span></span> <span data-ttu-id="731b3-126">使用可能な値が含まれます: '準備不完了'、'Error'、'警告'、'進行'、'良い'</span><span class="sxs-lookup"><span data-stu-id="731b3-126">Possible values include: 'NotReady', 'Error', 'Warning', 'Progressing', 'Good'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>