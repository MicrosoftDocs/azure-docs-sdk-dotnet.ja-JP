<Type Name="CertificateReference" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateReference">
  <TypeSignature Language="C#" Value="public class CertificateReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateReference" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateReference" />
  <TypeSignature Language="F#" Value="type CertificateReference = class" />
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
            <span data-ttu-id="7a835-101">プール内の計算ノードにインストールされている証明書への参照。</span><span class="sxs-lookup"><span data-stu-id="7a835-101">A reference to a certificate to be installed on compute nodes in a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.#ctor" />
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
            <span data-ttu-id="7a835-102">CertificateReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a835-102">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference (string thumbprint, string thumbprintAlgorithm, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; storeLocation = null, string storeName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; visibility = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; storeLocation, string storeName, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; visibility) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation},System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (thumbprint As String, thumbprintAlgorithm As String, Optional storeLocation As Nullable(Of CertificateStoreLocation) = null, Optional storeName As String = null, Optional visibility As IList(Of CertificateVisibility) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CertificateReference : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.CertificateReference (thumbprint, thumbprintAlgorithm, storeLocation, storeName, visibility)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt;" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="visibility" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprint"><span data-ttu-id="7a835-103">証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="7a835-103">The thumbprint of the certificate.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="7a835-104">拇印が関連付けられているアルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="7a835-104">The algorithm with which the thumbprint is associated.</span></span> <span data-ttu-id="7a835-105">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="7a835-105">This must be sha1.</span></span></param>
        <param name="storeLocation"><span data-ttu-id="7a835-106">証明書をインストールするコンピューティング ノード上の証明書ストアの場所です。</span><span class="sxs-lookup"><span data-stu-id="7a835-106">The location of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="storeName"><span data-ttu-id="7a835-107">証明書をインストールするコンピューティング ノードで証明書ストアの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a835-107">The name of the certificate store on the compute node into which to install the certificate.</span></span></param>
        <param name="visibility"><span data-ttu-id="7a835-108">コンピューティング ノード上でどのユーザー アカウントを使用すると、証明書のプライベート データへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7a835-108">Which user accounts on the compute node should have access to the private data of the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="7a835-109">CertificateReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a835-109">Initializes a new instance of the CertificateReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; StoreLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As Nullable(Of CertificateStoreLocation)" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a835-110">取得または証明書をインストールするコンピューティング ノードで、証明書ストアの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a835-110">Gets or sets the location of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7a835-111">既定値は currentuser です。</span><span class="sxs-lookup"><span data-stu-id="7a835-111">The default value is currentuser.</span></span> <span data-ttu-id="7a835-112">このプロパティは、Windows ノード (cloudServiceConfiguration では、作成または virtualMachineConfiguration、Windows を使用すると画像の参照) で構成されているプールにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="7a835-112">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span> <span data-ttu-id="7a835-113">Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。</span><span class="sxs-lookup"><span data-stu-id="7a835-113">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="7a835-114">'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。</span><span class="sxs-lookup"><span data-stu-id="7a835-114">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span> <span data-ttu-id="7a835-115">使用可能な値が含まれます: 'currentUser'、'localMachine'</span><span class="sxs-lookup"><span data-stu-id="7a835-115">Possible values include: 'currentUser', 'localMachine'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a835-116">取得または証明書をインストールするコンピューティング ノードで、証明書ストアの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a835-116">Gets or sets the name of the certificate store on the compute node into which to install the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7a835-117">このプロパティは、Windows ノード (cloudServiceConfiguration では、作成または virtualMachineConfiguration、Windows を使用すると画像の参照) で構成されているプールにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="7a835-117">This property is applicable only for pools configured with Windows nodes (that is, created with cloudServiceConfiguration, or with virtualMachineConfiguration using a Windows image reference).</span></span>
            <span data-ttu-id="7a835-118">一般的な店舗名が含まれます。 My、ルート、CA の信頼、、、[許可しない]、TrustedPeople、TrustedPublisher、AuthRoot、AddressBook、任意のカスタム ストア名も使用できます。</span><span class="sxs-lookup"><span data-stu-id="7a835-118">Common store names include: My, Root, CA, Trust, Disallowed, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, but any custom store name can also be used.</span></span> <span data-ttu-id="7a835-119">既定値は、My です。</span><span class="sxs-lookup"><span data-stu-id="7a835-119">The default value is My.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a835-120">取得または証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a835-120">Gets or sets the thumbprint of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a835-121">取得または拇印が関連付けられているアルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="7a835-121">Gets or sets the algorithm with which the thumbprint is associated.</span></span>
            <span data-ttu-id="7a835-122">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="7a835-122">This must be sha1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateReference.Validate " />
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
            <span data-ttu-id="7a835-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7a835-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7a835-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7a835-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Visibility">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; Visibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; Visibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Visibility" />
      <MemberSignature Language="VB.NET" Value="Public Property Visibility As IList(Of CertificateVisibility)" />
      <MemberSignature Language="F#" Value="member this.Visibility : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateReference.Visibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="visibility")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a835-125">取得または設定、証明書のプライベート データにコンピューティング ノード上でユーザー アカウントにアクセスする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a835-125">Gets or sets which user accounts on the compute node should have access to the private data of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="7a835-126">このコレクションでは、1 つ以上の可視性を指定できます。</span><span class="sxs-lookup"><span data-stu-id="7a835-126">You can specify more than one visibility in this collection.</span></span> <span data-ttu-id="7a835-127">既定値は、すべてのアカウントです。</span><span class="sxs-lookup"><span data-stu-id="7a835-127">The default is all accounts.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>