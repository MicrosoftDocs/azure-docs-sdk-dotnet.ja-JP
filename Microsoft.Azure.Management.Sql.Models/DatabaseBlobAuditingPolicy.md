<Type Name="DatabaseBlobAuditingPolicy" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy">
  <TypeSignature Language="C#" Value="public class DatabaseBlobAuditingPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseBlobAuditingPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseBlobAuditingPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DatabaseBlobAuditingPolicy = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="2d561-101">データベースは、監査ポリシーを blob です。</span><span class="sxs-lookup"><span data-stu-id="2d561-101">A database blob auditing policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBlobAuditingPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d561-102">DatabaseBlobAuditingPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d561-102">Initializes a new instance of the DatabaseBlobAuditingPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBlobAuditingPolicy (Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState state, string id = null, string name = null, string type = null, string kind = null, string storageEndpoint = null, string storageAccountAccessKey = null, Nullable&lt;int&gt; retentionDays = null, System.Collections.Generic.IList&lt;string&gt; auditActionsAndGroups = null, Nullable&lt;Guid&gt; storageAccountSubscriptionId = null, Nullable&lt;bool&gt; isStorageSecondaryKeyInUse = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState state, string id, string name, string type, string kind, string storageEndpoint, string storageAccountAccessKey, valuetype System.Nullable`1&lt;int32&gt; retentionDays, class System.Collections.Generic.IList`1&lt;string&gt; auditActionsAndGroups, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; storageAccountSubscriptionId, valuetype System.Nullable`1&lt;bool&gt; isStorageSecondaryKeyInUse) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.Nullable{System.Guid},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As BlobAuditingPolicyState, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As String = null, Optional storageEndpoint As String = null, Optional storageAccountAccessKey As String = null, Optional retentionDays As Nullable(Of Integer) = null, Optional auditActionsAndGroups As IList(Of String) = null, Optional storageAccountSubscriptionId As Nullable(Of Guid) = null, Optional isStorageSecondaryKeyInUse As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy : Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState * string * string * string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy (state, id, name, type, kind, storageEndpoint, storageAccountAccessKey, retentionDays, auditActionsAndGroups, storageAccountSubscriptionId, isStorageSecondaryKeyInUse)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="storageEndpoint" Type="System.String" />
        <Parameter Name="storageAccountAccessKey" Type="System.String" />
        <Parameter Name="retentionDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="auditActionsAndGroups" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="storageAccountSubscriptionId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="isStorageSecondaryKeyInUse" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="2d561-103">ポリシーの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-103">Specifies the state of the policy.</span></span> <span data-ttu-id="2d561-104">状態が有効になっている場合、storageEndpoint と storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-104">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="2d561-105">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="2d561-105">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="2d561-106">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="2d561-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="2d561-107">リソース名。</span><span class="sxs-lookup"><span data-stu-id="2d561-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="2d561-108">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2d561-108">Resource type.</span></span></param>
        <param name="kind"><span data-ttu-id="2d561-109">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2d561-109">Resource kind.</span></span></param>
        <param name="storageEndpoint"><span data-ttu-id="2d561-110">Blob ストレージ エンドポイント (例: https://MyAccount.blob.core.windows.net) を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-110">Specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="2d561-111">状態が有効になっている場合は、storageEndpoint が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-111">If state is Enabled, storageEndpoint is required.</span></span></param>
        <param name="storageAccountAccessKey"><span data-ttu-id="2d561-112">監査ストレージ アカウントのキー識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-112">Specifies the identifier key of the auditing storage account.</span></span> <span data-ttu-id="2d561-113">状態が有効になっている場合は、storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-113">If state is Enabled, storageAccountAccessKey is required.</span></span></param>
        <param name="retentionDays"><span data-ttu-id="2d561-114">監査ログに保持する日数の数を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-114">Specifies the number of days to keep in the audit logs.</span></span></param>
        <param name="auditActionsAndGroups"><span data-ttu-id="2d561-115">監査アクションおよびアクション グループを指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-115">Specifies the Actions and Actions-Groups to audit.</span></span></param>
        <param name="storageAccountSubscriptionId"><span data-ttu-id="2d561-116">Blob ストレージのサブスクリプション id を指定します</span><span class="sxs-lookup"><span data-stu-id="2d561-116">Specifies the blob storage subscription Id.</span></span></param>
        <param name="isStorageSecondaryKeyInUse"><span data-ttu-id="2d561-117">StorageAccountAccessKey 値が、記憶域のセカンダリ キーであるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-117">Specifies whether storageAccountAccessKey value is the storage’s secondary key.</span></span></param>
        <summary>
            <span data-ttu-id="2d561-118">DatabaseBlobAuditingPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d561-118">Initializes a new instance of the DatabaseBlobAuditingPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuditActionsAndGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AuditActionsAndGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AuditActionsAndGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.AuditActionsAndGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property AuditActionsAndGroups As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AuditActionsAndGroups : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.AuditActionsAndGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.auditActionsAndGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-119">取得または設定は、監査するには、アクションとアクション グループを指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-119">Gets or sets specifies the Actions and Actions-Groups to audit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStorageSecondaryKeyInUse">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsStorageSecondaryKeyInUse { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsStorageSecondaryKeyInUse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.IsStorageSecondaryKeyInUse" />
      <MemberSignature Language="VB.NET" Value="Public Property IsStorageSecondaryKeyInUse As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsStorageSecondaryKeyInUse : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.IsStorageSecondaryKeyInUse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isStorageSecondaryKeyInUse")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-120">取得または設定、storageAccountAccessKey 値が、記憶域のセカンダリ キーかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-120">Gets or sets specifies whether storageAccountAccessKey value is the storage’s secondary key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-121">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="2d561-121">Gets resource kind.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.RetentionDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.RetentionDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-122">取得または設定は、監査ログに保持する日数の数を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-122">Gets or sets specifies the number of days to keep in the audit logs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As BlobAuditingPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.State" />
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
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BlobAuditingPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-123">取得または設定は、ポリシーの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-123">Gets or sets specifies the state of the policy.</span></span> <span data-ttu-id="2d561-124">状態が有効になっている場合、storageEndpoint と storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-124">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="2d561-125">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="2d561-125">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountAccessKey">
      <MemberSignature Language="C#" Value="public string StorageAccountAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageAccountAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountAccessKey : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageAccountAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountAccessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-126">取得または設定は、監査ストレージ アカウントのキー識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-126">Gets or sets specifies the identifier key of the auditing storage account.</span></span> <span data-ttu-id="2d561-127">状態が有効になっている場合は、storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-127">If state is Enabled, storageAccountAccessKey is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountSubscriptionId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; StorageAccountSubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; StorageAccountSubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageAccountSubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountSubscriptionId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountSubscriptionId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageAccountSubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountSubscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-128">取得または設定は、blob ストレージのサブスクリプション id を指定します</span><span class="sxs-lookup"><span data-stu-id="2d561-128">Gets or sets specifies the blob storage subscription Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageEndpoint">
      <MemberSignature Language="C#" Value="public string StorageEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.StorageEndpoint : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.StorageEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d561-129">取得または設定は、blob ストレージ エンドポイント (例: https://MyAccount.blob.core.windows.net) を指定します。</span><span class="sxs-lookup"><span data-stu-id="2d561-129">Gets or sets specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="2d561-130">状態が有効になっている場合は、storageEndpoint が必要です。</span><span class="sxs-lookup"><span data-stu-id="2d561-130">If state is Enabled, storageEndpoint is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseBlobAuditingPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="databaseBlobAuditingPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d561-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2d561-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2d561-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2d561-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>