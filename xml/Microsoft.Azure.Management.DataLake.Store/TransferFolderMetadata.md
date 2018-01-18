<Type Name="TransferFolderMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata">
  <TypeSignature Language="C#" Value="public class TransferFolderMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderMetadata" />
  <TypeSignature Language="F#" Value="type TransferFolderMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("FileCount = {FileCount}, TransferId = {TransferId}, IsRecursive = {IsRecursive}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4991c-101">転送に関連する一般的なメタデータを表します。</span><span class="sxs-lookup"><span data-stu-id="4991c-101">Represents general metadata pertaining to a transfer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferFolderMetadata (string metadataFilePath, Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metadataFilePath, class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.#ctor(System.String,Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata : string * Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter -&gt; Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata (metadataFilePath, transferParameters, frontend)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metadataFilePath" Type="System.String" />
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontend" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
      </Parameters>
      <Docs>
        <param name="metadataFilePath"><span data-ttu-id="4991c-102">このメタデータ ファイル (目的を保存) するために割り当てるファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="4991c-102">The file path to assign to this metadata file (for saving purposes).</span></span></param>
        <param name="transferParameters"><span data-ttu-id="4991c-103">このメタデータを構築するために使用するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4991c-103">The parameters to use for constructing this metadata.</span></span></param>
        <param name="frontend"><span data-ttu-id="4991c-104">各ファイルのメタデータを生成するときに使用するフロント エンドです。</span><span class="sxs-lookup"><span data-stu-id="4991c-104">The frontend to use when generating per file metadata.</span></span></param>
        <summary>
            <span data-ttu-id="4991c-105">指定したパラメーターから新しい TransferFolderMetadata オブジェクトを構築します。</span><span class="sxs-lookup"><span data-stu-id="4991c-105">Constructs a new TransferFolderMetadata object from the given parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferFolderMetadata.DeleteFile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4991c-106">メタデータ ファイルをディスクから削除します。</span><span class="sxs-lookup"><span data-stu-id="4991c-106">Deletes the metadata file from disk.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4991c-107">Null または空の MetadataFilePath します。</span><span class="sxs-lookup"><span data-stu-id="4991c-107">Null or empty MetadataFilePath.</span></span> <span data-ttu-id="4991c-108">このプロパティが設定されるまで、メタデータを削除することはできません。</span><span class="sxs-lookup"><span data-stu-id="4991c-108">Cannot delete metadata until this property is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public int FileCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FileCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-109">取得または転送でこのファイルの数を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="4991c-109">Gets or sets a value indicating the number of files in this transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-110">セグメントの数。</span><span class="sxs-lookup"><span data-stu-id="4991c-110">The segment count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As TransferMetadata()" />
      <MemberSignature Language="F#" Value="member this.Files : Microsoft.Azure.Management.DataLake.Store.TransferMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-111">ファイル転送のメタデータの配列へのポインターを取得します。</span><span class="sxs-lookup"><span data-stu-id="4991c-111">Gets a pointer to an array of file transfer metadata.</span></span> <span data-ttu-id="4991c-112">これは、各ファイルの転送中に使用されます。</span><span class="sxs-lookup"><span data-stu-id="4991c-112">This is used for each file that is being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-113">セグメント。</span><span class="sxs-lookup"><span data-stu-id="4991c-113">The segments.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFolderPath">
      <MemberSignature Language="C#" Value="public string InputFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.InputFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.InputFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-114">取得または転送するファイルへの完全パスを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="4991c-114">Gets or sets a value indicating the full path to the file to be transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-115">入力ファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="4991c-115">The input file path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.IsRecursive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsRecursive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-116">フラットなディレクトリの転送や recurisve ディレクトリの転送であるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="4991c-116">Gets a value indicating whether this is recurisve directory transfer or a flat directory transfer</span></span>
            </summary>
        <value>
          <span data-ttu-id="4991c-117"><c>true</c>場合、このインスタンスが再帰的です。 それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="4991c-117"><c>true</c> if this instance is recursive; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Save">
      <MemberSignature Language="C#" Value="public void Save ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Save() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.Save" />
      <MemberSignature Language="VB.NET" Value="Public Sub Save ()" />
      <MemberSignature Language="F#" Value="member this.Save : unit -&gt; unit" Usage="transferFolderMetadata.Save " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4991c-118">指定したメタデータを標準的な場所に保存します。</span><span class="sxs-lookup"><span data-stu-id="4991c-118">Saves the given metadata to its canonical location.</span></span> <span data-ttu-id="4991c-119">このメソッドは、スレッド セーフです。</span><span class="sxs-lookup"><span data-stu-id="4991c-119">This method is thread-safe.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamFolderPath">
      <MemberSignature Language="C#" Value="public string TargetStreamFolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamFolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TargetStreamFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamFolderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-120">取得またはファイルとフォルダーが転送されるすべてのルート フォルダーとして使用されるストリーム全体のフォルダーのパスを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="4991c-120">Gets or sets a value indicating the full stream folder path that will be used as the root folder for all files and folders being transferred.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-121">ターゲット ストリーム パス。</span><span class="sxs-lookup"><span data-stu-id="4991c-121">The target stream path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileBytes">
      <MemberSignature Language="C#" Value="public long TotalFileBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalFileBytes As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileBytes : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TotalFileBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TotalFileBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-122">取得またはすべてのファイルの合計バイト数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4991c-122">Gets or sets the total bytes for all the files.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-123">すべてのファイルの合計バイト数。</span><span class="sxs-lookup"><span data-stu-id="4991c-123">The total bytes for all the files.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderMetadata.TransferId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TransferId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4991c-124">取得またはこの譲渡に関連付けられている一意の識別子を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="4991c-124">Gets or sets a value indicating the unique identifier associated with this transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4991c-125">転送の識別子です。</span><span class="sxs-lookup"><span data-stu-id="4991c-125">The transfer identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>