<Type Name="SyncAgent" FullName="Microsoft.Azure.Management.Sql.Models.SyncAgent">
  <TypeSignature Language="C#" Value="public class SyncAgent : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncAgent extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncAgent" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncAgent&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type SyncAgent = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="89304-101">Azure SQL データベースの同期エージェントです。</span><span class="sxs-lookup"><span data-stu-id="89304-101">An Azure SQL Database sync agent.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncAgent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncAgent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89304-102">SyncAgent クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89304-102">Initializes a new instance of the SyncAgent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncAgent (string id = null, string name = null, string type = null, string syncAgentName = null, string syncDatabaseId = null, Nullable&lt;DateTime&gt; lastAliveTime = null, string state = null, Nullable&lt;bool&gt; isUpToDate = null, Nullable&lt;DateTime&gt; expiryTime = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string syncAgentName, string syncDatabaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastAliveTime, string state, valuetype System.Nullable`1&lt;bool&gt; isUpToDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncAgent.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional syncAgentName As String = null, Optional syncDatabaseId As String = null, Optional lastAliveTime As Nullable(Of DateTime) = null, Optional state As String = null, Optional isUpToDate As Nullable(Of Boolean) = null, Optional expiryTime As Nullable(Of DateTime) = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncAgent : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncAgent" Usage="new Microsoft.Azure.Management.Sql.Models.SyncAgent (id, name, type, syncAgentName, syncDatabaseId, lastAliveTime, state, isUpToDate, expiryTime, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="syncAgentName" Type="System.String" />
        <Parameter Name="syncDatabaseId" Type="System.String" />
        <Parameter Name="lastAliveTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="isUpToDate" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="89304-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="89304-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="89304-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="89304-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="89304-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="89304-105">Resource type.</span></span></param>
        <param name="syncAgentName"><span data-ttu-id="89304-106">同期エージェントの名前です。</span><span class="sxs-lookup"><span data-stu-id="89304-106">Name of the sync agent.</span></span></param>
        <param name="syncDatabaseId"><span data-ttu-id="89304-107">同期エージェントで、sync データベースの ARM リソース id です。</span><span class="sxs-lookup"><span data-stu-id="89304-107">ARM resource id of the sync database in the sync agent.</span></span></param>
        <param name="lastAliveTime"><span data-ttu-id="89304-108">同期エージェントがアライブの最後の時刻。</span><span class="sxs-lookup"><span data-stu-id="89304-108">Last alive time of the sync agent.</span></span></param>
        <param name="state"><span data-ttu-id="89304-109">同期エージェントの状態です。</span><span class="sxs-lookup"><span data-stu-id="89304-109">State of the sync agent.</span></span> <span data-ttu-id="89304-110">使用可能な値が含まれます: 'オンライン'、'Offline'、'NeverConnected'</span><span class="sxs-lookup"><span data-stu-id="89304-110">Possible values include: 'Online', 'Offline', 'NeverConnected'</span></span></param>
        <param name="isUpToDate"><span data-ttu-id="89304-111">同期エージェントのバージョンが最新の状態の場合は。</span><span class="sxs-lookup"><span data-stu-id="89304-111">If the sync agent version is up to date.</span></span></param>
        <param name="expiryTime"><span data-ttu-id="89304-112">同期エージェントのバージョンの有効期限。</span><span class="sxs-lookup"><span data-stu-id="89304-112">Expiration time of the sync agent version.</span></span></param>
        <param name="version"><span data-ttu-id="89304-113">同期エージェントのバージョンです。</span><span class="sxs-lookup"><span data-stu-id="89304-113">Version of the sync agent.</span></span></param>
        <summary>
            <span data-ttu-id="89304-114">SyncAgent クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89304-114">Initializes a new instance of the SyncAgent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expiryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-115">同期エージェントのバージョンの有効期限を取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-115">Gets expiration time of the sync agent version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUpToDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUpToDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUpToDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.IsUpToDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsUpToDate As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUpToDate : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.IsUpToDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isUpToDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-116">場合は、同期エージェントのバージョンが最新の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-116">Gets if the sync agent version is up to date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAliveTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastAliveTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastAliveTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.LastAliveTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAliveTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastAliveTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.LastAliveTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastAliveTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-117">同期エージェントの最後の存続時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-117">Gets last alive time of the sync agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-118">同期エージェントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-118">Gets state of the sync agent.</span></span> <span data-ttu-id="89304-119">使用可能な値が含まれます: 'オンライン'、'Offline'、'NeverConnected'</span><span class="sxs-lookup"><span data-stu-id="89304-119">Possible values include: 'Online', 'Offline', 'NeverConnected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncAgentName">
      <MemberSignature Language="C#" Value="public string SyncAgentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncAgentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.SyncAgentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncAgentName As String" />
      <MemberSignature Language="F#" Value="member this.SyncAgentName : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.SyncAgentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-120">同期エージェントの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-120">Gets name of the sync agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncDatabaseId">
      <MemberSignature Language="C#" Value="public string SyncDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SyncDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.SyncDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SyncDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SyncDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.SyncDatabaseId" />
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
            <span data-ttu-id="89304-121">取得または同期エージェントで、sync データベースの ARM リソース id を設定します。</span><span class="sxs-lookup"><span data-stu-id="89304-121">Gets or sets ARM resource id of the sync database in the sync agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncAgent.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncAgent.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89304-122">同期エージェントのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="89304-122">Gets version of the sync agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>