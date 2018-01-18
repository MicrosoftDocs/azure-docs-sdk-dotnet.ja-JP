<Type Name="PoolPatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter">
  <TypeSignature Language="C#" Value="public class PoolPatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolPatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolPatchParameter" />
  <TypeSignature Language="F#" Value="type PoolPatchParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="44ff4-101">プールへの変更のセット。</span><span class="sxs-lookup"><span data-stu-id="44ff4-101">The set of changes to be made to a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolPatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-102">PoolPatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-102">Initializes a new instance of the PoolPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolPatchParameter (Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter : Microsoft.Azure.Batch.Protocol.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter (startTask, certificateReferences, applicationPackageReferences, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="startTask"><span data-ttu-id="44ff4-103">各コンピューティング ノード上で実行するタスクは、プールを結合します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-103">A task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="44ff4-104">タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-104">The task runs when the node is added to the pool or when the node is restarted.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="44ff4-105">プール内の各コンピューティング ノードにインストールされている証明書の一覧。</span><span class="sxs-lookup"><span data-stu-id="44ff4-105">A list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="44ff4-106">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</span><span class="sxs-lookup"><span data-stu-id="44ff4-106">A list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="44ff4-107">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="44ff4-107">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="44ff4-108">PoolPatchParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-108">Initializes a new instance of the PoolPatchParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-109">取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-109">Gets or sets a list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="44ff4-110">アプリケーション パッケージの参照の変更は、プールに参加するすべての新しいコンピューティング ノードには影響が、コンピューティング ノードを再起動または再イメージ化されるまで、プールに既に存在するには影響しません。</span><span class="sxs-lookup"><span data-stu-id="44ff4-110">Changes to application package references affect all new compute nodes joining the pool, but do not affect compute nodes that are already in the pool until they are rebooted or reimaged.</span></span> <span data-ttu-id="44ff4-111">この要素が存在する場合は、既存のアプリケーション パッケージ参照が置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-111">If this element is present, it replaces any existing application package references.</span></span> <span data-ttu-id="44ff4-112">空のコレクションを指定する場合、アプリケーション パッケージのすべての参照は、プールから削除されます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-112">If you specify an empty collection, then all application package references are removed from the pool.</span></span> <span data-ttu-id="44ff4-113">省略した場合、参照のままにする既存のアプリケーション パッケージは変更されません。</span><span class="sxs-lookup"><span data-stu-id="44ff4-113">If omitted, any existing application package references are left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-114">取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-114">Gets or sets a list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="44ff4-115">この要素が存在する場合は、プールに構成されている既存の証明書参照が置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-115">If this element is present, it replaces any existing certificate references configured on the pool.</span></span> <span data-ttu-id="44ff4-116">省略した場合、参照のままにする既存の証明書は変更されません。</span><span class="sxs-lookup"><span data-stu-id="44ff4-116">If omitted, any existing certificate references are left unchanged.</span></span> <span data-ttu-id="44ff4-117">Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。</span><span class="sxs-lookup"><span data-stu-id="44ff4-117">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="44ff4-118">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-118">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="44ff4-119">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-119">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-120">取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-120">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="44ff4-121">この要素が存在する場合は、プールに構成されている既存のメタデータが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-121">If this element is present, it replaces any existing metadata configured on the pool.</span></span> <span data-ttu-id="44ff4-122">空のコレクションを指定する場合、すべてのメタデータはプールから削除されます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-122">If you specify an empty collection, any metadata is removed from the pool.</span></span> <span data-ttu-id="44ff4-123">既存のメタデータが左で省略すると、変更されません。</span><span class="sxs-lookup"><span data-stu-id="44ff4-123">If omitted, any existing metadata is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-124">取得またはプールを結合として各コンピューティング ノード上で実行するタスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-124">Gets or sets a task to run on each compute node as it joins the pool.</span></span> <span data-ttu-id="44ff4-125">タスクは、プールに、または、ノードが再起動されたときに、ノードが追加されたときに実行されます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-125">The task runs when the node is added to the pool or when the node is restarted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="44ff4-126">この要素が存在する場合は、既存の開始タスクが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-126">If this element is present, it overwrites any existing start task.</span></span>
            <span data-ttu-id="44ff4-127">既存の開始タスクが左で省略すると、変更されません。</span><span class="sxs-lookup"><span data-stu-id="44ff4-127">If omitted, any existing start task is left unchanged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolPatchParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44ff4-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="44ff4-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="44ff4-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="44ff4-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>