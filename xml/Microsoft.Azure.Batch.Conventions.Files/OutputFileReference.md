<Type Name="OutputFileReference" FullName="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference">
  <TypeSignature Language="C#" Value="public sealed class OutputFileReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OutputFileReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OutputFileReference" />
  <TypeSignature Language="F#" Value="type OutputFileReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="16b69-101">永続的ストレージにタスクまたはジョブの出力ファイルへの参照。</span><span class="sxs-lookup"><span data-stu-id="16b69-101">A reference to a task or job output file in persistent storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloudBlob">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.ICloudBlob CloudBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob CloudBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.CloudBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloudBlob As ICloudBlob" />
      <MemberSignature Language="F#" Value="member this.CloudBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.CloudBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.ICloudBlob</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16b69-102">基になるへの参照を取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />永続的ストレージにファイルを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="16b69-102">Gets a reference to the underlying <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> object representing the file in persistent storage.</span></span> <span data-ttu-id="16b69-103">これは、blob のメソッドまたはには表示されませんのオーバー ロードを呼び出す使用できる、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" />抽象化します。</span><span class="sxs-lookup"><span data-stu-id="16b69-103">This can be used to invoke blob methods or overloads not surfaced by the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" /> abstraction.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="16b69-104">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="16b69-104">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="16b69-105">永続的なストレージからファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="16b69-105">Deletes the file from persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="16b69-106">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="16b69-106">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DeleteAsync" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToByteArrayAsync(System.Byte[],System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToByteArrayAsync : byte[] * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="outputFileReference.DownloadToByteArrayAsync (target, index, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToByteArrayAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="16b69-107">対象のバイト配列。</span><span class="sxs-lookup"><span data-stu-id="16b69-107">The target byte array.</span></span></param>
        <param name="index"><span data-ttu-id="16b69-108">バイト配列内の開始オフセット</span><span class="sxs-lookup"><span data-stu-id="16b69-108">The starting offset in the byte array</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="16b69-109">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="16b69-109">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="16b69-110">ファイルの内容をバイト配列にダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="16b69-110">Downloads the contents of the file to a byte array.</span></span>
            </summary>
        <returns><span data-ttu-id="16b69-111">バッファーに読み取られた合計バイト数。</span><span class="sxs-lookup"><span data-stu-id="16b69-111">The total number of bytes read into the buffer.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32)" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToFileAsync(System.String,System.IO.FileMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToFileAsync : string * System.IO.FileMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DownloadToFileAsync (path, mode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToFileAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="16b69-112">ファイルをダウンロードするためのパス。</span><span class="sxs-lookup"><span data-stu-id="16b69-112">The path to which to download the file.</span></span></param>
        <param name="mode"><span data-ttu-id="16b69-113">開くか、ファイルを作成する方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="16b69-113">Specifies how to open or create the file.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="16b69-114">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="16b69-114">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="16b69-115">指定されたパスにファイルの内容をダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="16b69-115">Downloads the contents of the file to a specified path.</span></span>
            </summary>
        <returns><span data-ttu-id="16b69-116">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="16b69-116">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode)" />
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.DownloadToStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DownloadToStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="outputFileReference.DownloadToStreamAsync (target, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;DownloadToStreamAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="16b69-117">対象のストリーム。</span><span class="sxs-lookup"><span data-stu-id="16b69-117">The target stream.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="16b69-118">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="16b69-118">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="16b69-119">ファイルの内容をストリームにダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="16b69-119">Downloads the contents of the file to a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="16b69-120">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="16b69-120">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.DownloadToStreamAsync(System.IO.Stream)" />
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16b69-121">ファイルが格納されているパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="16b69-121">Gets the path under which the file was stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="16b69-122">ファイルは、ディレクトリのパスの下に格納された、FilePath プロパティは、基になる blob ストレージ (たとえば、mydirectory/myfile.txt) のディレクトリの区切り記号を使用します。</span><span class="sxs-lookup"><span data-stu-id="16b69-122">If the file was stored under a directory path, the FilePath property uses the directory separator of the underlying blob storage (for example, mydirectory/myfile.txt).</span></span> <span data-ttu-id="16b69-123">このようなパスは、Windows のパスとして直接使用できない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="16b69-123">Such paths may not be directly usable as Windows paths.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.OpenReadAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.OpenReadAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="outputFileReference.OpenReadAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.OutputFileReference/&lt;OpenReadAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="16b69-124">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="16b69-124">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="16b69-125">永続的ストレージ内のファイルから読み取るのためのストリームを開きます。</span><span class="sxs-lookup"><span data-stu-id="16b69-125">Opens a stream for reading from the file in persistent storage.</span></span>
            </summary>
        <returns><span data-ttu-id="16b69-126">Blob からの読み取りに使用するストリーム。</span><span class="sxs-lookup"><span data-stu-id="16b69-126">A stream to be used for reading from the blob.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob.OpenReadAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.Azure.Batch.Conventions.Files.OutputFileReference.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16b69-127">永続的ストレージ内のファイルの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="16b69-127">Gets the URI of the file in persistent storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>