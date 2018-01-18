<Type Name="FileServer" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServer">
  <TypeSignature Language="C#" Value="public class FileServer : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServer extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServer" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServer&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type FileServer = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="23da7-101">ファイル サーバーに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="23da7-101">Contains information about the File Server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23da7-102">FileServer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23da7-102">Initializes a new instance of the FileServer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServer (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string vmSize = null, Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null, Microsoft.Azure.Management.BatchAI.Models.MountSettings mountSettings = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState.Creating);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, class Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet, class Microsoft.Azure.Management.BatchAI.Models.MountSettings mountSettings, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.BatchAI.Models.SshConfiguration,Microsoft.Azure.Management.BatchAI.Models.DataDisks,Microsoft.Azure.Management.BatchAI.Models.ResourceId,Microsoft.Azure.Management.BatchAI.Models.MountSettings,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServer : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.BatchAI.Models.SshConfiguration * Microsoft.Azure.Management.BatchAI.Models.DataDisks * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Microsoft.Azure.Management.BatchAI.Models.MountSettings * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServer (id, name, type, location, tags, vmSize, sshConfiguration, dataDisks, subnet, mountSettings, provisioningStateTransitionTime, creationTime, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="sshConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" />
        <Parameter Name="dataDisks" Type="Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="mountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.MountSettings" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="23da7-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="23da7-103">The ID of the resource</span></span></param>
        <param name="name"><span data-ttu-id="23da7-104">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="23da7-104">The name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="23da7-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="23da7-105">The type of the resource</span></span></param>
        <param name="location"><span data-ttu-id="23da7-106">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="23da7-106">The location of the resource</span></span></param>
        <param name="tags"><span data-ttu-id="23da7-107">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="23da7-107">The tags of the resource</span></span></param>
        <param name="vmSize"><span data-ttu-id="23da7-108">ファイル サーバーの仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="23da7-108">The size of the virtual machine of the File Server.</span></span></param>
        <param name="sshConfiguration"><span data-ttu-id="23da7-109">ファイル サーバーの SSH 設定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-109">SSH settings for the File Server.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="23da7-110">ファイル サーバーの作成とデータ ディスクの設定です。</span><span class="sxs-lookup"><span data-stu-id="23da7-110">Settings for the data disk which would be created for the File Server.</span></span></param>
        <param name="subnet"><span data-ttu-id="23da7-111">サブネットの識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-111">Specifies the identifier of the subnet.</span></span></param>
        <param name="mountSettings"><span data-ttu-id="23da7-112">ファイル サーバーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="23da7-112">Details of the File Server.</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="23da7-113">状態が変更された時刻。</span><span class="sxs-lookup"><span data-stu-id="23da7-113">Time when the status was changed.</span></span></param>
        <param name="creationTime"><span data-ttu-id="23da7-114">ファイル サーバーが作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="23da7-114">Time when the FileServer was created.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="23da7-115">ファイル サーバーのプロビジョニングの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-115">Specifies the provisioning state of the File Server.</span></span></param>
        <summary>
            <span data-ttu-id="23da7-116">FileServer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23da7-116">Initializes a new instance of the FileServer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-117">ファイル サーバーの作成日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="23da7-117">Gets time when the FileServer was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As DataDisks" />
      <MemberSignature Language="F#" Value="member this.DataDisks : Microsoft.Azure.Management.BatchAI.Models.DataDisks with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.DataDisks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-118">取得またはファイル サーバーの作成とデータ ディスクの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-118">Gets or sets settings for the data disk which would be created for the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.MountSettings MountSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.MountSettings MountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.MountSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MountSettings As MountSettings" />
      <MemberSignature Language="F#" Value="member this.MountSettings : Microsoft.Azure.Management.BatchAI.Models.MountSettings" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.MountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.MountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-119">ファイル サーバーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="23da7-119">Gets details of the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As FileServerProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-120">取得では、ファイル サーバーのプロビジョニングの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-120">Gets specifies the provisioning state of the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="23da7-121">使用可能な値: 作成、ファイル サーバーの作成中です。</span><span class="sxs-lookup"><span data-stu-id="23da7-121">Possible values: creating - The File Server is getting created.</span></span>
            <span data-ttu-id="23da7-122">更新 - ファイル サーバーの作成が受け付けられるし、は更新を取得します。</span><span class="sxs-lookup"><span data-stu-id="23da7-122">updating - The File Server creation has been accepted and it is getting updated.</span></span> <span data-ttu-id="23da7-123">削除すると、ユーザーがファイル サーバーが削除されることを要求し、は、削除されている処理中です。</span><span class="sxs-lookup"><span data-stu-id="23da7-123">deleting - The user has requested that the File Server be deleted, and it is in the process of being deleted.</span></span>
            <span data-ttu-id="23da7-124">失敗しました - 指定したエラー コードとファイル サーバーの作成に失敗しました。</span><span class="sxs-lookup"><span data-stu-id="23da7-124">failed - The File Server creation has failed with the specified errorCode.</span></span> <span data-ttu-id="23da7-125">エラー コードに関する詳細については、[メッセージ] フィールドで指定されます。</span><span class="sxs-lookup"><span data-stu-id="23da7-125">Details about the error code are specified in the message field.</span></span> <span data-ttu-id="23da7-126">成功 - ファイル サーバーの作成は成功しました。</span><span class="sxs-lookup"><span data-stu-id="23da7-126">succeeded - The File Server creation has succeeded.</span></span>
            <span data-ttu-id="23da7-127">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="23da7-127">Possible values include: 'creating', 'updating', 'deleting', 'succeeded', 'failed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-128">状態が変更された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="23da7-128">Gets time when the status was changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.SshConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property SshConfiguration As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.SshConfiguration : Microsoft.Azure.Management.BatchAI.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.SshConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sshConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-129">取得またはファイル サーバーの SSH の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-129">Gets or sets SSH settings for the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-130">取得または設定は、サブネットの識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-130">Gets or sets specifies the identifier of the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23da7-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="23da7-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23da7-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23da7-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23da7-133">取得またはファイル サーバーの仮想マシンのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="23da7-133">Gets or sets the size of the virtual machine of the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="23da7-134">仮想マシン Marketplace からファイル サーバーの利用可能な VM サイズについては、仮想マシン (Linux) のサイズを参照してください。</span><span class="sxs-lookup"><span data-stu-id="23da7-134">For information about available VM sizes for File Server from the Virtual Machines Marketplace, see Sizes for Virtual Machines (Linux).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>