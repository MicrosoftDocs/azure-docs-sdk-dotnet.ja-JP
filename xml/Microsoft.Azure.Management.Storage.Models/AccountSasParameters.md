<Type Name="AccountSasParameters" FullName="Microsoft.Azure.Management.Storage.Models.AccountSasParameters">
  <TypeSignature Language="C#" Value="public class AccountSasParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccountSasParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AccountSasParameters" />
  <TypeSignature Language="F#" Value="type AccountSasParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="09d30-101">ストレージ アカウントの SAS 資格情報を一覧するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="09d30-101">The parameters to list SAS credentials of a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccountSasParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09d30-102">AccountSasParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="09d30-102">Initializes a new instance of the AccountSasParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccountSasParameters (string services, string resourceTypes, string permissions, DateTime sharedAccessExpiryTime, string iPAddressOrRange = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; protocols = null, Nullable&lt;DateTime&gt; sharedAccessStartTime = null, string keyToSign = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string services, string resourceTypes, string permissions, valuetype System.DateTime sharedAccessExpiryTime, string iPAddressOrRange, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; protocols, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sharedAccessStartTime, string keyToSign) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.#ctor(System.String,System.String,System.String,System.DateTime,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.HttpProtocol},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (services As String, resourceTypes As String, permissions As String, sharedAccessExpiryTime As DateTime, Optional iPAddressOrRange As String = null, Optional protocols As Nullable(Of HttpProtocol) = null, Optional sharedAccessStartTime As Nullable(Of DateTime) = null, Optional keyToSign As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.AccountSasParameters : string * string * string * DateTime * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Storage.Models.AccountSasParameters" Usage="new Microsoft.Azure.Management.Storage.Models.AccountSasParameters (services, resourceTypes, permissions, sharedAccessExpiryTime, iPAddressOrRange, protocols, sharedAccessStartTime, keyToSign)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="services" Type="System.String" />
        <Parameter Name="resourceTypes" Type="System.String" />
        <Parameter Name="permissions" Type="System.String" />
        <Parameter Name="sharedAccessExpiryTime" Type="System.DateTime" />
        <Parameter Name="iPAddressOrRange" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt;" />
        <Parameter Name="sharedAccessStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="keyToSign" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="services"><span data-ttu-id="09d30-103">署名付きサービス アカウント SAS でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="09d30-103">The signed services accessible with the account SAS.</span></span> <span data-ttu-id="09d30-104">使用可能な値が含まれます: Blob (b)、キュー (q)、テーブル (t)、ファイル (f)。</span><span class="sxs-lookup"><span data-stu-id="09d30-104">Possible values include: Blob (b), Queue (q), Table (t), File (f).</span></span> <span data-ttu-id="09d30-105">使用可能な値が含まれます: 'b'、'q'、' t '、'f'</span><span class="sxs-lookup"><span data-stu-id="09d30-105">Possible values include: 'b', 'q', 't', 'f'</span></span></param>
        <param name="resourceTypes"><span data-ttu-id="09d30-106">SA アカウントでアクセス可能な符号付きのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="09d30-106">The signed resource types that are accessible with the account SAS.</span></span> <span data-ttu-id="09d30-107">サービス (s): サービス レベル Api; へのアクセスコンテナー (c): コンテナー レベル Api; へのアクセスオブジェクト (o): blob、メッセージ キュー、テーブル エンティティ、およびファイルのオブジェクト レベルの Api にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="09d30-107">Service (s): Access to service-level APIs; Container (c): Access to container-level APIs; Object (o): Access to object-level APIs for blobs, queue messages, table entities, and files.</span></span> <span data-ttu-id="09d30-108">使用可能な値が含まれますの '、'c'、' o '。</span><span class="sxs-lookup"><span data-stu-id="09d30-108">Possible values include: 's', 'c', 'o'</span></span></param>
        <param name="permissions"><span data-ttu-id="09d30-109">SA アカウントの符号付きのアクセス許可。</span><span class="sxs-lookup"><span data-stu-id="09d30-109">The signed permissions for the account SAS.</span></span> <span data-ttu-id="09d30-110">使用可能な値が含まれます: 読み取り (r)、書き込み (w)、Delete (d)、リスト (l)、(a) の追加、作成 (c) 更新 (u) および (p) を処理します。</span><span class="sxs-lookup"><span data-stu-id="09d30-110">Possible values include: Read (r), Write (w), Delete (d), List (l), Add (a), Create (c), Update (u) and Process (p).</span></span> <span data-ttu-id="09d30-111">使用可能な値が含まれます: 'r' に指定された受信者 '、'w'、'l'、'a', 'c'、'u'、'p'</span><span class="sxs-lookup"><span data-stu-id="09d30-111">Possible values include: 'r', 'd', 'w', 'l', 'a', 'c', 'u', 'p'</span></span></param>
        <param name="sharedAccessExpiryTime"><span data-ttu-id="09d30-112">共有アクセス署名が無効になる時刻。</span><span class="sxs-lookup"><span data-stu-id="09d30-112">The time at which the shared access signature becomes invalid.</span></span></param>
        <param name="iPAddressOrRange"><span data-ttu-id="09d30-113">IP アドレスまたは元の要求を受け入れるための範囲の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="09d30-113">An IP address or a range of IP addresses from which to accept requests.</span></span></param>
        <param name="protocols"><span data-ttu-id="09d30-114">SA アカウントを使用して行われた要求のプロトコルが許可されます。</span><span class="sxs-lookup"><span data-stu-id="09d30-114">The protocol permitted for a request made with the account SAS.</span></span> <span data-ttu-id="09d30-115">使用可能な値が含まれます 'https, http'、'https'。</span><span class="sxs-lookup"><span data-stu-id="09d30-115">Possible values include: 'https,http', 'https'</span></span></param>
        <param name="sharedAccessStartTime"><span data-ttu-id="09d30-116">SAS が有効になる時刻。</span><span class="sxs-lookup"><span data-stu-id="09d30-116">The time at which the SAS becomes valid.</span></span></param>
        <param name="keyToSign"><span data-ttu-id="09d30-117">アカウントの SAS トークンを署名するキー。</span><span class="sxs-lookup"><span data-stu-id="09d30-117">The key to sign the account SAS token with.</span></span></param>
        <summary>
            <span data-ttu-id="09d30-118">AccountSasParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="09d30-118">Initializes a new instance of the AccountSasParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrRange">
      <MemberSignature Language="C#" Value="public string IPAddressOrRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddressOrRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.IPAddressOrRange" />
      <MemberSignature Language="VB.NET" Value="Public Property IPAddressOrRange As String" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrRange : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.IPAddressOrRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedIp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-119">取得または IP アドレスまたは元の要求を受け入れるための範囲の IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-119">Gets or sets an IP address or a range of IP addresses from which to accept requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyToSign">
      <MemberSignature Language="C#" Value="public string KeyToSign { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyToSign" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.KeyToSign" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyToSign As String" />
      <MemberSignature Language="F#" Value="member this.KeyToSign : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.KeyToSign" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyToSign")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-120">取得またはのアカウント SAS トークンの署名にキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-120">Gets or sets the key to sign the account SAS token with.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public string Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As String" />
      <MemberSignature Language="F#" Value="member this.Permissions : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedPermission")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-121">取得またはアカウント SAS の符号付きのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-121">Gets or sets the signed permissions for the account SAS.</span></span> <span data-ttu-id="09d30-122">使用可能な値が含まれます: 読み取り (r)、書き込み (w)、Delete (d)、リスト (l)、(a) の追加、作成 (c) 更新 (u) および (p) を処理します。</span><span class="sxs-lookup"><span data-stu-id="09d30-122">Possible values include: Read (r), Write (w), Delete (d), List (l), Add (a), Create (c), Update (u) and Process (p).</span></span> <span data-ttu-id="09d30-123">使用可能な値が含まれます: 'r' に指定された受信者 '、'w'、'l'、'a', 'c'、'u'、'p'</span><span class="sxs-lookup"><span data-stu-id="09d30-123">Possible values include: 'r', 'd', 'w', 'l', 'a', 'c', 'u', 'p'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocols">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; Protocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; Protocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Protocols" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocols As Nullable(Of HttpProtocol)" />
      <MemberSignature Language="F#" Value="member this.Protocols : Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Protocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedProtocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.HttpProtocol&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-124">取得またはアカウント SAS を使用して行われた要求に許可されるプロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-124">Gets or sets the protocol permitted for a request made with the account SAS.</span></span> <span data-ttu-id="09d30-125">使用可能な値が含まれます 'https, http'、'https'。</span><span class="sxs-lookup"><span data-stu-id="09d30-125">Possible values include: 'https,http', 'https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceTypes">
      <MemberSignature Language="C#" Value="public string ResourceTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.ResourceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceTypes As String" />
      <MemberSignature Language="F#" Value="member this.ResourceTypes : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.ResourceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedResourceTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-126">取得またはアカウント SAS でアクセス可能な符号付きのリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-126">Gets or sets the signed resource types that are accessible with the account SAS.</span></span> <span data-ttu-id="09d30-127">サービス (s): サービス レベル Api; へのアクセスコンテナー (c): コンテナー レベル Api; へのアクセスオブジェクト (o): blob、メッセージ キュー、テーブル エンティティ、およびファイルのオブジェクト レベルの Api にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="09d30-127">Service (s): Access to service-level APIs; Container (c): Access to container-level APIs; Object (o): Access to object-level APIs for blobs, queue messages, table entities, and files.</span></span> <span data-ttu-id="09d30-128">使用可能な値が含まれますの '、'c'、' o '。</span><span class="sxs-lookup"><span data-stu-id="09d30-128">Possible values include: 's', 'c', 'o'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Services">
      <MemberSignature Language="C#" Value="public string Services { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Services" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Services" />
      <MemberSignature Language="VB.NET" Value="Public Property Services As String" />
      <MemberSignature Language="F#" Value="member this.Services : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Services" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedServices")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-129">取得または符号付きのサービスをアカウント SAS でアクセスできるように設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-129">Gets or sets the signed services accessible with the account SAS.</span></span>
            <span data-ttu-id="09d30-130">使用可能な値が含まれます: Blob (b)、キュー (q)、テーブル (t)、ファイル (f)。</span><span class="sxs-lookup"><span data-stu-id="09d30-130">Possible values include: Blob (b), Queue (q), Table (t), File (f).</span></span>
            <span data-ttu-id="09d30-131">使用可能な値が含まれます: 'b'、'q'、' t '、'f'</span><span class="sxs-lookup"><span data-stu-id="09d30-131">Possible values include: 'b', 'q', 't', 'f'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public DateTime SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedExpiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-132">取得または共有アクセス署名が無効になる時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-132">Gets or sets the time at which the shared access signature becomes invalid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.AccountSasParameters.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signedStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09d30-133">取得または SAS が有効になる時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="09d30-133">Gets or sets the time at which the SAS becomes valid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.AccountSasParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="accountSasParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09d30-134">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="09d30-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="09d30-135">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09d30-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>