<Type Name="FileProperties" FullName="Microsoft.WindowsAzure.Storage.File.FileProperties">
  <TypeSignature Language="C#" Value="public sealed class FileProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileProperties" />
  <TypeSignature Language="F#" Value="type FileProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="30226-101">ファイルのシステム プロパティを表します。</span><span class="sxs-lookup"><span data-stu-id="30226-101">Represents the system properties for a file.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="30226-102"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileProperties" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="30226-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.FileProperties" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileProperties (Microsoft.WindowsAzure.Storage.File.FileProperties other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.File.FileProperties other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileProperties.#ctor(Microsoft.WindowsAzure.Storage.File.FileProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As FileProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.FileProperties : Microsoft.WindowsAzure.Storage.File.FileProperties -&gt; Microsoft.WindowsAzure.Storage.File.FileProperties" Usage="new Microsoft.WindowsAzure.Storage.File.FileProperties other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="30226-103">複製するファイルのプロパティのセット。</span><span class="sxs-lookup"><span data-stu-id="30226-103">The set of file properties to clone.</span></span></param>
        <summary>
            <span data-ttu-id="30226-104">新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.File.FileProperties" />クラスは、既存のインスタンスに基づいています。</span><span class="sxs-lookup"><span data-stu-id="30226-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.FileProperties" /> class based on an existing instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-105">取得または格納されているファイルの cache-control 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-105">Gets or sets the cache-control value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-106">ファイルの cache-control 値です。</span><span class="sxs-lookup"><span data-stu-id="30226-106">The file's cache-control value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-107">取得または格納されているファイルの content-disposition 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-107">Gets or sets the content-disposition value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-108">ファイルの content-disposition 値です。</span><span class="sxs-lookup"><span data-stu-id="30226-108">The file's content-disposition value.</span></span></value>
        <remarks>
            <span data-ttu-id="30226-109">ファイルのこのプロパティが設定されていない場合、null を返します。</span><span class="sxs-lookup"><span data-stu-id="30226-109">If this property has not been set for the file, it returns null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-110">取得または格納されているファイルの content-encoding 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-110">Gets or sets the content-encoding value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-111">ファイルの content-encoding 値です。</span><span class="sxs-lookup"><span data-stu-id="30226-111">The file's content-encoding value.</span></span></value>
        <remarks>
            <span data-ttu-id="30226-112">このプロパティが設定されていないかどうか、ファイルをそれを返します<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="30226-112">If this property has not been set for the file, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-113">取得または格納されているファイルの content-language 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-113">Gets or sets the content-language value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-114">ファイルの content-language 値です。</span><span class="sxs-lookup"><span data-stu-id="30226-114">The file's content-language value.</span></span></value>
        <remarks>
            <span data-ttu-id="30226-115">このプロパティが設定されていないかどうか、ファイルをそれを返します<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="30226-115">If this property has not been set for the file, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentMD5">
      <MemberSignature Language="C#" Value="public string ContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentMD5 As String" />
      <MemberSignature Language="F#" Value="member this.ContentMD5 : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-116">取得またはファイルの格納されている content-md5 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-116">Gets or sets the content-MD5 value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-117">ファイルの content-md5 ハッシュです。</span><span class="sxs-lookup"><span data-stu-id="30226-117">The file's content-MD5 hash.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-118">取得またはファイルの格納されているコンテンツの種類の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="30226-118">Gets or sets the content-type value stored for the file.</span></span>
            </summary>
        <value><span data-ttu-id="30226-119">ファイルのコンテンツの種類の値です。</span><span class="sxs-lookup"><span data-stu-id="30226-119">The file's content-type value.</span></span></value>
        <remarks>
            <span data-ttu-id="30226-120">このプロパティが設定されていないかどうか、ファイルをそれを返します<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="30226-120">If this property has not been set for the file, it returns <c>null</c>.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-121">ファイルの ETag 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="30226-121">Gets the file's ETag value.</span></span>
            </summary>
        <value><span data-ttu-id="30226-122">ファイルの ETag 値です。</span><span class="sxs-lookup"><span data-stu-id="30226-122">The file's ETag value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.IsServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.IsServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-123">ファイルのサーバー側暗号化の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="30226-123">Gets the file's server-side encryption state.</span></span>
            </summary>
        <value><span data-ttu-id="30226-124">ファイルのサーバー側の暗号化の状態を表すブール値。</span><span class="sxs-lookup"><span data-stu-id="30226-124">A bool representing the file's server-side encryption state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-125">取得、ファイルの最終更新時刻が UTC 値として表されます。</span><span class="sxs-lookup"><span data-stu-id="30226-125">Gets the the last-modified time for the file, expressed as a UTC value.</span></span>
            </summary>
        <value><span data-ttu-id="30226-126">ファイルの最終更新時刻を UTC 形式でします。</span><span class="sxs-lookup"><span data-stu-id="30226-126">The file's last-modified time, in UTC format.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileProperties.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.File.FileProperties.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30226-127">(バイト単位)、ファイルのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="30226-127">Gets the size of the file, in bytes.</span></span>
            </summary>
        <value><span data-ttu-id="30226-128">ファイルのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="30226-128">The file's size in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>