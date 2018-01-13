<Type Name="SqlDWSink" FullName="Microsoft.Azure.Management.DataFactories.Models.SqlDWSink">
  <TypeSignature Language="C#" Value="public class SqlDWSink : Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlDWSink extends Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlDWSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type SqlDWSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ba32f-101">コピー アクティビティ SQL データ ウェアハウスのシンク。</span><span class="sxs-lookup"><span data-stu-id="ba32f-101">A copy activity SQL data warehouse sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ba32f-102">SqlDWSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba32f-102">Initializes a new instance of the SqlDWSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlDWSink (int writeBatchSize, TimeSpan writeBatchTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 writeBatchSize, valuetype System.TimeSpan writeBatchTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.#ctor(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (writeBatchSize As Integer, writeBatchTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SqlDWSink : int * TimeSpan -&gt; Microsoft.Azure.Management.DataFactories.Models.SqlDWSink" Usage="new Microsoft.Azure.Management.DataFactories.Models.SqlDWSink (writeBatchSize, writeBatchTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="writeBatchSize" Type="System.Int32" />
        <Parameter Name="writeBatchTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="writeBatchSize">To be added.</param>
        <param name="writeBatchTimeout">To be added.</param>
        <summary>
            <span data-ttu-id="ba32f-103">必須の引数で SqlDWSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ba32f-103">Initializes a new instance of the SqlDWSink class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowPolyBase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowPolyBase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowPolyBase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.AllowPolyBase" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowPolyBase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowPolyBase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.AllowPolyBase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba32f-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba32f-104">Optional.</span></span> <span data-ttu-id="ba32f-105">True の場合は、以下の条件をすべて満たしているときに、SQL データ ウェアハウスにデータをコピーする PolyBase を使用します。</span><span class="sxs-lookup"><span data-stu-id="ba32f-105">If true, use PolyBase to copy data into SQL Data Warehouse when all below criteria are met:</span></span>
            1. <span data-ttu-id="ba32f-106">ソースがリンクされているサービスである必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageLinkedService" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-106">Source linked service must be <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureStorageLinkedService" />.</span></span>
            2. <span data-ttu-id="ba32f-107">ソース データセットである必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-107">Source dataset must be <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset" />.</span></span>
            3. <span data-ttu-id="ba32f-108">ソース データセットの形式にする必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.TextFormat" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-108">Format of source dataset must be <see cref="T:Microsoft.Azure.Management.DataFactories.Models.TextFormat" />.</span></span>
            5. <span data-ttu-id="ba32f-109">ソース データセットの形式の EncodingName は"utf-8"である必要があります。</span><span class="sxs-lookup"><span data-stu-id="ba32f-109">EncodingName of source dataset format must be "utf-8".</span></span>
            6. <span data-ttu-id="ba32f-110">ソース データセットの形式の RowDelimiter は"\n"である必要があります。</span><span class="sxs-lookup"><span data-stu-id="ba32f-110">RowDelimiter of source dataset format must be "\n".</span></span>
            7. <span data-ttu-id="ba32f-111">NullValue のソースのデータセット形式にする必要があります<see cref="F:System.String.Empty" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-111">NullValue of source dataset format must be <see cref="F:System.String.Empty" />.</span></span>
            8. <span data-ttu-id="ba32f-112">ソース データセットの圧縮のみをサポート<see cref="T:Microsoft.Azure.Management.DataFactories.Models.GZipCompression" />と<see cref="T:Microsoft.Azure.Management.DataFactories.Models.DeflateCompression" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-112">Compression of source dataset only supports <see cref="T:Microsoft.Azure.Management.DataFactories.Models.GZipCompression" /> and <see cref="T:Microsoft.Azure.Management.DataFactories.Models.DeflateCompression" />.</span></span>
            9. <span data-ttu-id="ba32f-113">ソースである必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.BlobSource" />です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-113">Source must be <see cref="T:Microsoft.Azure.Management.DataFactories.Models.BlobSource" />.</span></span>
            <span data-ttu-id="ba32f-114">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="ba32f-114">Default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolyBaseSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings PolyBaseSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings PolyBaseSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.PolyBaseSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property PolyBaseSettings As PolyBaseSettings" />
      <MemberSignature Language="F#" Value="member this.PolyBaseSettings : Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.PolyBaseSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba32f-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba32f-115">Optional.</span></span> <span data-ttu-id="ba32f-116">AllowPolyBase が true の場合は、PolyBase 関連の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="ba32f-116">Specifies PolyBase-related settings when AllowPolyBase is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceIdentifierColumnName">
      <MemberSignature Language="C#" Value="public string SliceIdentifierColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceIdentifierColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.SliceIdentifierColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceIdentifierColumnName As String" />
      <MemberSignature Language="F#" Value="member this.SliceIdentifierColumnName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.SliceIdentifierColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba32f-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba32f-117">Optional.</span></span> <span data-ttu-id="ba32f-118">べき等なのでコピーをサポートするために、スライスの識別子情報の保存に使用される SQL 列の名前。</span><span class="sxs-lookup"><span data-stu-id="ba32f-118">Name of the SQL column which is used to save slice identifier information, to support idempotent copy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlWriterCleanupScript">
      <MemberSignature Language="C#" Value="public string SqlWriterCleanupScript { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlWriterCleanupScript" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.SqlWriterCleanupScript" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlWriterCleanupScript As String" />
      <MemberSignature Language="F#" Value="member this.SqlWriterCleanupScript : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlDWSink.SqlWriterCleanupScript" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba32f-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="ba32f-119">Optional.</span></span> <span data-ttu-id="ba32f-120">SQL ライター クリーンアップ スクリプトです。</span><span class="sxs-lookup"><span data-stu-id="ba32f-120">SQL writer cleanup script.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>