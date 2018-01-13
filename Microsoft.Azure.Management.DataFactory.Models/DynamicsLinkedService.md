<Type Name="DynamicsLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService">
  <TypeSignature Language="C#" Value="public class DynamicsLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DynamicsLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class DynamicsLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type DynamicsLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Dynamics")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="38bcc-101">Dynamics リンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="38bcc-101">Dynamics linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-102">DynamicsLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-102">Initializes a new instance of the DynamicsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicsLinkedService (object deploymentType, object authenticationType, object username, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object hostName = null, object port = null, object organizationName = null, Microsoft.Azure.Management.DataFactory.Models.SecretBase password = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object deploymentType, object authenticationType, object username, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object hostName, object port, object organizationName, class Microsoft.Azure.Management.DataFactory.Models.SecretBase password, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.#ctor(System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecretBase,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentType As Object, authenticationType As Object, username As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional hostName As Object = null, Optional port As Object = null, Optional organizationName As Object = null, Optional password As SecretBase = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService : obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecretBase * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService (deploymentType, authenticationType, username, additionalProperties, connectVia, description, hostName, port, organizationName, password, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentType" Type="System.Object" />
        <Parameter Name="authenticationType" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="hostName" Type="System.Object" />
        <Parameter Name="port" Type="System.Object" />
        <Parameter Name="organizationName" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecretBase" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deploymentType"><span data-ttu-id="38bcc-103">Dynamics インスタンスの展開の種類。</span><span class="sxs-lookup"><span data-stu-id="38bcc-103">The deployment type of the Dynamics instance.</span></span> <span data-ttu-id="38bcc-104">Dynamics オンラインおよび Dynamics の 'OnPremisesWithIfd' の' オンライン' でオンプレミス Ifd です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-104">'Online' for Dynamics Online and 'OnPremisesWithIfd' for Dynamics on-premises with Ifd.</span></span> <span data-ttu-id="38bcc-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="authenticationType"><span data-ttu-id="38bcc-106">Dynamics サーバーに接続する認証の種類。</span><span class="sxs-lookup"><span data-stu-id="38bcc-106">The authentication type to connect to Dynamics server.</span></span> <span data-ttu-id="38bcc-107">'Office 365' オンライン シナリオでは、Ifd シナリオで、内部設置型の ' Ifd' です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-107">'Office365' for online scenario, 'Ifd' for on-premises with Ifd scenario.</span></span> <span data-ttu-id="38bcc-108">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-108">Type: string (or Expression with resultType string).</span></span></param>
        <param name="username"><span data-ttu-id="38bcc-109">Dynamics インスタンスにアクセスするユーザー名。</span><span class="sxs-lookup"><span data-stu-id="38bcc-109">User name to access the Dynamics instance.</span></span>
            <span data-ttu-id="38bcc-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="38bcc-111">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="38bcc-111">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="38bcc-112">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="38bcc-112">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="38bcc-113">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="38bcc-113">Linked service description.</span></span></param>
        <param name="hostName"><span data-ttu-id="38bcc-114">内部設置型 Dynamics サーバーのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-114">The host name of the on-premises Dynamics server.</span></span> <span data-ttu-id="38bcc-115">プロパティは、オンプレミスに必要なおり、オンラインを使用できません。</span><span class="sxs-lookup"><span data-stu-id="38bcc-115">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="38bcc-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="port"><span data-ttu-id="38bcc-117">オンプレミス Dynamics サーバーのポート。</span><span class="sxs-lookup"><span data-stu-id="38bcc-117">The port of on-premises Dynamics server.</span></span> <span data-ttu-id="38bcc-118">プロパティは、オンプレミスに必要なおり、オンラインを使用できません。</span><span class="sxs-lookup"><span data-stu-id="38bcc-118">The property is required for on-prem and not allowed for online.</span></span>
            <span data-ttu-id="38bcc-119">既定は 443 です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-119">Default is 443.</span></span> <span data-ttu-id="38bcc-120">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="38bcc-120">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="organizationName"><span data-ttu-id="38bcc-121">Dynamics インスタンスの組織の名前。</span><span class="sxs-lookup"><span data-stu-id="38bcc-121">The organization name of the Dynamics instance.</span></span> <span data-ttu-id="38bcc-122">プロパティは、オンプレミスの必須でありに必要なオンライン ユーザーに関連付けられている Dynamics インスタンスが 1 つ以上の場合。</span><span class="sxs-lookup"><span data-stu-id="38bcc-122">The property is required for on-prem and required for online when there are more than one Dynamics instances associated with the user.</span></span> <span data-ttu-id="38bcc-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-123">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="38bcc-124">Dynamics インスタンスにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="38bcc-124">Password to access the Dynamics instance.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="38bcc-125">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-125">The encrypted credential used for authentication.</span></span> <span data-ttu-id="38bcc-126">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="38bcc-126">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="38bcc-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-127">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="38bcc-128">DynamicsLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-128">Initializes a new instance of the DynamicsLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public object AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As Object" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.authenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-129">取得または Dynamics サーバーに接続する認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-129">Gets or sets the authentication type to connect to Dynamics server.</span></span>
            <span data-ttu-id="38bcc-130">'Office 365' オンライン シナリオでは、Ifd シナリオで、内部設置型の ' Ifd' です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-130">'Office365' for online scenario, 'Ifd' for on-premises with Ifd scenario.</span></span> <span data-ttu-id="38bcc-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentType">
      <MemberSignature Language="C#" Value="public object DeploymentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DeploymentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.DeploymentType" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentType As Object" />
      <MemberSignature Language="F#" Value="member this.DeploymentType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.DeploymentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.deploymentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-132">取得または Dynamics インスタンスの展開の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-132">Gets or sets the deployment type of the Dynamics instance.</span></span> <span data-ttu-id="38bcc-133">Dynamics オンラインおよび Dynamics の 'OnPremisesWithIfd' の' オンライン' でオンプレミス Ifd です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-133">'Online' for Dynamics Online and 'OnPremisesWithIfd' for Dynamics on-premises with Ifd.</span></span> <span data-ttu-id="38bcc-134">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-134">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-135">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-135">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="38bcc-136">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="38bcc-136">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="38bcc-137">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-137">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public object HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As Object" />
      <MemberSignature Language="F#" Value="member this.HostName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-138">取得または内部設置型の Dynamics サーバーのホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-138">Gets or sets the host name of the on-premises Dynamics server.</span></span> <span data-ttu-id="38bcc-139">プロパティは、オンプレミスに必要なおり、オンラインを使用できません。</span><span class="sxs-lookup"><span data-stu-id="38bcc-139">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="38bcc-140">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-140">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrganizationName">
      <MemberSignature Language="C#" Value="public object OrganizationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OrganizationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.OrganizationName" />
      <MemberSignature Language="VB.NET" Value="Public Property OrganizationName As Object" />
      <MemberSignature Language="F#" Value="member this.OrganizationName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.OrganizationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.organizationName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-141">取得または Dynamics インスタンスの組織の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-141">Gets or sets the organization name of the Dynamics instance.</span></span> <span data-ttu-id="38bcc-142">プロパティは、オンプレミスの必須でありに必要なオンライン ユーザーに関連付けられている Dynamics インスタンスが 1 つ以上の場合。</span><span class="sxs-lookup"><span data-stu-id="38bcc-142">The property is required for on-prem and required for online when there are more than one Dynamics instances associated with the user.</span></span>
            <span data-ttu-id="38bcc-143">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-143">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecretBase Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecretBase Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecretBase" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecretBase with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecretBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-144">取得または Dynamics インスタンスにアクセスするためのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-144">Gets or sets password to access the Dynamics instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public object Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Object" />
      <MemberSignature Language="F#" Value="member this.Port : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-145">取得または内部設置型 Dynamics サーバーのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-145">Gets or sets the port of on-premises Dynamics server.</span></span> <span data-ttu-id="38bcc-146">プロパティは、オンプレミスに必要なおり、オンラインを使用できません。</span><span class="sxs-lookup"><span data-stu-id="38bcc-146">The property is required for on-prem and not allowed for online.</span></span> <span data-ttu-id="38bcc-147">既定は 443 です。</span><span class="sxs-lookup"><span data-stu-id="38bcc-147">Default is 443.</span></span>
            <span data-ttu-id="38bcc-148">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="38bcc-148">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-149">取得または Dynamics インスタンスにアクセスするユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-149">Gets or sets user name to access the Dynamics instance.</span></span> <span data-ttu-id="38bcc-150">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="38bcc-150">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DynamicsLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dynamicsLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="38bcc-151">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="38bcc-151">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="38bcc-152">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="38bcc-152">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>