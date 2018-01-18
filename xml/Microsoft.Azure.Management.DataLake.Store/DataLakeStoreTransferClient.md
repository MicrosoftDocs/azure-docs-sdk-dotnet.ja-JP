<Type Name="DataLakeStoreTransferClient" FullName="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient">
  <TypeSignature Language="C#" Value="public sealed class DataLakeStoreTransferClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataLakeStoreTransferClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataLakeStoreTransferClient" />
  <TypeSignature Language="F#" Value="type DataLakeStoreTransferClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2d31b-101">Data Lake Store に一般的な用途にファイル転送クライアントを表します。</span><span class="sxs-lookup"><span data-stu-id="2d31b-101">Represents a general purpose file transfer client into a Data Lake Store.</span></span> <span data-ttu-id="2d31b-102">大きなファイルの効率的な転送をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="2d31b-102">Supports the efficient transfer of large files.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreTransferClient (Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.#ctor(Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient : Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient (transferParameters, frontEnd, progressTracker, folderProgressTracker)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontEnd" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="folderProgressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
      </Parameters>
      <Docs>
        <param name="transferParameters"><span data-ttu-id="2d31b-103">使用する転送パラメーター。</span><span class="sxs-lookup"><span data-stu-id="2d31b-103">The transfer parameters to use.</span></span></param>
        <param name="frontEnd"><span data-ttu-id="2d31b-104">転送に使用するフロント エンド インターフェイスへのポインター。</span><span class="sxs-lookup"><span data-stu-id="2d31b-104">A pointer to the FrontEnd interface to use for the transfer.</span></span></param>
        <param name="progressTracker"><span data-ttu-id="2d31b-105">(省略可能)転送に関する進行状況を報告するトラッカーです。</span><span class="sxs-lookup"><span data-stu-id="2d31b-105">(Optional) A tracker that reports progress on the transfer.</span></span></param>
        <param name="folderProgressTracker"><span data-ttu-id="2d31b-106">(省略可能)フォルダーの進行状況の追跡ツール。</span><span class="sxs-lookup"><span data-stu-id="2d31b-106">(Optional) The folder progress tracker.</span></span></param>
        <summary>
            <span data-ttu-id="2d31b-107">転送に使用するフロント エンドへのポインターを指定することによって、DataLakeStoreTransferClient クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2d31b-107">Creates a new instance of the DataLakeStoreTransferClient class, by specifying a pointer to the FrontEnd to use for the transfer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreTransferClient (Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, System.Threading.CancellationToken token, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, valuetype System.Threading.CancellationToken token, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.#ctor(Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter,System.Threading.CancellationToken,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient : Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter * System.Threading.CancellationToken * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient (transferParameters, frontEnd, token, progressTracker, folderProgressTracker)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontEnd" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="folderProgressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
      </Parameters>
      <Docs>
        <param name="transferParameters"><span data-ttu-id="2d31b-108">転送に使用するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="2d31b-108">The transfer Parameters to use.</span></span></param>
        <param name="frontEnd"><span data-ttu-id="2d31b-109">転送に使用するフロント エンド インターフェイスへのポインター。</span><span class="sxs-lookup"><span data-stu-id="2d31b-109">A pointer to the FrontEnd interface to use for the transfer.</span></span></param>
        <param name="token"><span data-ttu-id="2d31b-110">トークン。</span><span class="sxs-lookup"><span data-stu-id="2d31b-110">The token.</span></span></param>
        <param name="progressTracker"><span data-ttu-id="2d31b-111">(省略可能)転送に関する進行状況を報告するトラッカーです。</span><span class="sxs-lookup"><span data-stu-id="2d31b-111">(Optional) A tracker that reports progress on the transfer.</span></span></param>
        <param name="folderProgressTracker"><span data-ttu-id="2d31b-112">(省略可能)フォルダーの進行状況の追跡ツール。</span><span class="sxs-lookup"><span data-stu-id="2d31b-112">(Optional) The folder progress tracker.</span></span></param>
        <summary>
            <span data-ttu-id="2d31b-113">転送に使用するフロント エンドへのポインターを指定することによって、DataLakeStoreTransferClient クラスの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2d31b-113">Creates a new instance of the DataLakeStoreTransferClient class, by specifying a pointer to the FrontEnd to use for the transfer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public void Execute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Execute() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Execute" />
      <MemberSignature Language="VB.NET" Value="Public Sub Execute ()" />
      <MemberSignature Language="F#" Value="member this.Execute : unit -&gt; unit" Usage="dataLakeStoreTransferClient.Execute " />
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
            <span data-ttu-id="2d31b-114">入力パラメーターで定義されている転送を実行します。</span><span class="sxs-lookup"><span data-stu-id="2d31b-114">Executes the transfer as defined by the input parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedThreadsPerFile">
      <MemberSignature Language="C#" Value="public const int MaxAllowedThreadsPerFile = 1024;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxAllowedThreadsPerFile = (1024)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.MaxAllowedThreadsPerFile" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxAllowedThreadsPerFile As Integer  = 1024" />
      <MemberSignature Language="F#" Value="val mutable MaxAllowedThreadsPerFile : int" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.MaxAllowedThreadsPerFile" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>1024</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d31b-115">使用する並列スレッドの最大数。</span><span class="sxs-lookup"><span data-stu-id="2d31b-115">The maximum number of parallel threads to allow.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnFileTransferThreadFailProgressUpdate">
      <MemberSignature Language="C#" Value="public event Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate OnFileTransferThreadFailProgressUpdate;" />
      <MemberSignature Language="ILAsm" Value=".event class Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate OnFileTransferThreadFailProgressUpdate" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.OnFileTransferThreadFailProgressUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Event OnFileTransferThreadFailProgressUpdate As FileTransferThreadFailProgressUpdate " />
      <MemberSignature Language="F#" Value="member this.OnFileTransferThreadFailProgressUpdate : Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate " Usage="member this.OnFileTransferThreadFailProgressUpdate : Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="2d31b-116">進行状況の追跡に予期しない転送エラーが発生した場合の進行状況が正しく更新されていることを確認するに登録されているイベントです。</span><span class="sxs-lookup"><span data-stu-id="2d31b-116">An event that is registered to progress tracking to ensure that, in the event of an unexpected transfer failure, progress is properly updated.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferParameters Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As TransferParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d31b-117">この転送に使用するパラメーターを取得します。</span><span class="sxs-lookup"><span data-stu-id="2d31b-117">Gets the parameters to use for this transfer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>