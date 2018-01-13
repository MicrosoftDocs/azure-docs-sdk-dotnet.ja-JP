<Type Name="DatabaseSecurityAlertPolicy" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy">
  <TypeSignature Language="C#" Value="public class DatabaseSecurityAlertPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseSecurityAlertPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseSecurityAlertPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DatabaseSecurityAlertPolicy = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="85b20-101">脅威検出ポリシーのデータベースに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="85b20-101">Contains information about a database Threat Detection policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseSecurityAlertPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85b20-102">DatabaseSecurityAlertPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85b20-102">Initializes a new instance of the DatabaseSecurityAlertPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseSecurityAlertPolicy (Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState state, string id = null, string name = null, string type = null, string location = null, string kind = null, string disabledAlerts = null, string emailAddresses = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; emailAccountAdmins = null, string storageEndpoint = null, string storageAccountAccessKey = null, Nullable&lt;int&gt; retentionDays = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; useServerDefault = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState state, string id, string name, string type, string location, string kind, string disabledAlerts, string emailAddresses, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; emailAccountAdmins, string storageEndpoint, string storageAccountAccessKey, valuetype System.Nullable`1&lt;int32&gt; retentionDays, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; useServerDefault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins},System.String,System.String,System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As SecurityAlertPolicyState, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional kind As String = null, Optional disabledAlerts As String = null, Optional emailAddresses As String = null, Optional emailAccountAdmins As Nullable(Of SecurityAlertPolicyEmailAccountAdmins) = null, Optional storageEndpoint As String = null, Optional storageAccountAccessKey As String = null, Optional retentionDays As Nullable(Of Integer) = null, Optional useServerDefault As Nullable(Of SecurityAlertPolicyUseServerDefault) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy : Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState * string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy (state, id, name, type, location, kind, disabledAlerts, emailAddresses, emailAccountAdmins, storageEndpoint, storageAccountAccessKey, retentionDays, useServerDefault)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="disabledAlerts" Type="System.String" />
        <Parameter Name="emailAddresses" Type="System.String" />
        <Parameter Name="emailAccountAdmins" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt;" />
        <Parameter Name="storageEndpoint" Type="System.String" />
        <Parameter Name="storageAccountAccessKey" Type="System.String" />
        <Parameter Name="retentionDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useServerDefault" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt;" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="85b20-103">ポリシーの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-103">Specifies the state of the policy.</span></span> <span data-ttu-id="85b20-104">状態が有効になっている場合、storageEndpoint と storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-104">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="85b20-105">使用可能な値が含まれます 'New'、'Enabled'、'Disabled'。</span><span class="sxs-lookup"><span data-stu-id="85b20-105">Possible values include: 'New', 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="85b20-106">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="85b20-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="85b20-107">リソース名。</span><span class="sxs-lookup"><span data-stu-id="85b20-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="85b20-108">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="85b20-108">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="85b20-109">リソースが存在する地理的な場所</span><span class="sxs-lookup"><span data-stu-id="85b20-109">The geo-location where the resource lives</span></span></param>
        <param name="kind"><span data-ttu-id="85b20-110">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="85b20-110">Resource kind.</span></span></param>
        <param name="disabledAlerts"><span data-ttu-id="85b20-111">アラートが無効または空の警告を無効にない文字列をセミコロンで区切られた一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-111">Specifies the semicolon-separated list of alerts that are disabled, or empty string to disable no alerts.</span></span>
            <span data-ttu-id="85b20-112">使用可能な値: Sql_Injection です。Sql_Injection_Vulnerability です。Access_Anomaly です。Usage_Anomaly です。</span><span class="sxs-lookup"><span data-stu-id="85b20-112">Possible values: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span></span></param>
        <param name="emailAddresses"><span data-ttu-id="85b20-113">アラートを送信する電子メール アドレスのセミコロンで区切った一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-113">Specifies the semicolon-separated list of e-mail addresses to which the alert is sent.</span></span></param>
        <param name="emailAccountAdmins"><span data-ttu-id="85b20-114">アカウント管理者にアラートを送信することを指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-114">Specifies that the alert is sent to the account administrators.</span></span> <span data-ttu-id="85b20-115">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="85b20-115">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="storageEndpoint"><span data-ttu-id="85b20-116">Blob ストレージ エンドポイント (例: https://MyAccount.blob.core.windows.net) を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-116">Specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="85b20-117">この blob ストレージでは、脅威検出機能のすべての監査ログを保持します。</span><span class="sxs-lookup"><span data-stu-id="85b20-117">This blob storage will hold all Threat Detection audit logs.</span></span> <span data-ttu-id="85b20-118">状態が有効になっている場合は、storageEndpoint が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-118">If state is Enabled, storageEndpoint is required.</span></span></param>
        <param name="storageAccountAccessKey"><span data-ttu-id="85b20-119">脅威検出監査ストレージ アカウントのキー識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-119">Specifies the identifier key of the Threat Detection audit storage account.</span></span> <span data-ttu-id="85b20-120">状態が有効になっている場合は、storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-120">If state is Enabled, storageAccountAccessKey is required.</span></span></param>
        <param name="retentionDays"><span data-ttu-id="85b20-121">脅威検出機能の監査ログに保持する日数の数を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-121">Specifies the number of days to keep in the Threat Detection audit logs.</span></span></param>
        <param name="useServerDefault"><span data-ttu-id="85b20-122">既定のサーバー ポリシーを使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-122">Specifies whether to use the default server policy.</span></span> <span data-ttu-id="85b20-123">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="85b20-123">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="85b20-124">DatabaseSecurityAlertPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85b20-124">Initializes a new instance of the DatabaseSecurityAlertPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledAlerts">
      <MemberSignature Language="C#" Value="public string DisabledAlerts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisabledAlerts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.DisabledAlerts" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledAlerts As String" />
      <MemberSignature Language="F#" Value="member this.DisabledAlerts : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.DisabledAlerts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disabledAlerts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-125">取得または設定は、アラートを無効の場合、または空のないアラートを無効にする文字列のセミコロンで区切られた一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-125">Gets or sets specifies the semicolon-separated list of alerts that are disabled, or empty string to disable no alerts.</span></span> <span data-ttu-id="85b20-126">使用可能な値: Sql_Injection です。Sql_Injection_Vulnerability です。Access_Anomaly です。Usage_Anomaly です。</span><span class="sxs-lookup"><span data-stu-id="85b20-126">Possible values: Sql_Injection; Sql_Injection_Vulnerability; Access_Anomaly; Usage_Anomaly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAccountAdmins">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; EmailAccountAdmins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; EmailAccountAdmins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAccountAdmins" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAccountAdmins As Nullable(Of SecurityAlertPolicyEmailAccountAdmins)" />
      <MemberSignature Language="F#" Value="member this.EmailAccountAdmins : Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAccountAdmins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailAccountAdmins")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyEmailAccountAdmins&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-127">取得または設定は、アカウント管理者にアラートを送信することを指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-127">Gets or sets specifies that the alert is sent to the account administrators.</span></span> <span data-ttu-id="85b20-128">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="85b20-128">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddresses">
      <MemberSignature Language="C#" Value="public string EmailAddresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAddresses" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddresses As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddresses : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.EmailAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.emailAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-129">取得または設定は、アラートを送信する電子メール アドレスのセミコロンで区切った一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-129">Gets or sets specifies the semicolon-separated list of e-mail addresses to which the alert is sent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Kind" />
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
            <span data-ttu-id="85b20-130">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="85b20-130">Gets resource kind.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-131">取得またはリソースが存在する場所を地理的な場所に設定</span><span class="sxs-lookup"><span data-stu-id="85b20-131">Gets or sets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.RetentionDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.RetentionDays" />
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
            <span data-ttu-id="85b20-132">取得または設定は、脅威の検出の監査ログに保持する日数の数を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-132">Gets or sets specifies the number of days to keep in the Threat Detection audit logs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As SecurityAlertPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.State" />
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
        <ReturnType>Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-133">取得または設定は、ポリシーの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-133">Gets or sets specifies the state of the policy.</span></span> <span data-ttu-id="85b20-134">状態が有効になっている場合、storageEndpoint と storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-134">If state is Enabled, storageEndpoint and storageAccountAccessKey are required.</span></span>
            <span data-ttu-id="85b20-135">使用可能な値が含まれます 'New'、'Enabled'、'Disabled'。</span><span class="sxs-lookup"><span data-stu-id="85b20-135">Possible values include: 'New', 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountAccessKey">
      <MemberSignature Language="C#" Value="public string StorageAccountAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageAccountAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountAccessKey : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageAccountAccessKey" />
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
            <span data-ttu-id="85b20-136">取得または設定は、脅威の検出監査ストレージ アカウントのキー識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-136">Gets or sets specifies the identifier key of the Threat Detection audit storage account.</span></span> <span data-ttu-id="85b20-137">状態が有効になっている場合は、storageAccountAccessKey が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-137">If state is Enabled, storageAccountAccessKey is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageEndpoint">
      <MemberSignature Language="C#" Value="public string StorageEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.StorageEndpoint : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.StorageEndpoint" />
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
            <span data-ttu-id="85b20-138">取得または設定は、blob ストレージ エンドポイント (例: https://MyAccount.blob.core.windows.net) を指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-138">Gets or sets specifies the blob storage endpoint (e.g. https://MyAccount.blob.core.windows.net).</span></span> <span data-ttu-id="85b20-139">この blob ストレージでは、脅威検出機能のすべての監査ログを保持します。</span><span class="sxs-lookup"><span data-stu-id="85b20-139">This blob storage will hold all Threat Detection audit logs.</span></span> <span data-ttu-id="85b20-140">状態が有効になっている場合は、storageEndpoint が必要です。</span><span class="sxs-lookup"><span data-stu-id="85b20-140">If state is Enabled, storageEndpoint is required.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseServerDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; UseServerDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; UseServerDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.UseServerDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseServerDefault As Nullable(Of SecurityAlertPolicyUseServerDefault)" />
      <MemberSignature Language="F#" Value="member this.UseServerDefault : Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.UseServerDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.useServerDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.SecurityAlertPolicyUseServerDefault&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85b20-141">取得または設定は、既定のサーバー ポリシーを使用するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="85b20-141">Gets or sets specifies whether to use the default server policy.</span></span>
            <span data-ttu-id="85b20-142">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="85b20-142">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="databaseSecurityAlertPolicy.Validate " />
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
            <span data-ttu-id="85b20-143">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="85b20-143">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="85b20-144">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85b20-144">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>