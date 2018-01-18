<Type Name="TransferStatus" FullName="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus">
  <TypeSignature Language="C#" Value="public class TransferStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferStatus" />
  <TypeSignature Language="F#" Value="type TransferStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e5b6e-101">転送の状態に関する情報が含まれています</span><span class="sxs-lookup"><span data-stu-id="e5b6e-101">Contains information regarding Transfer status</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChunksTransfered">
      <MemberSignature Language="C#" Value="public long ChunksTransfered;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 ChunksTransfered" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.ChunksTransfered" />
      <MemberSignature Language="VB.NET" Value="Public ChunksTransfered As Long " />
      <MemberSignature Language="F#" Value="val mutable ChunksTransfered : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.ChunksTransfered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-102">チャンクのトラック数が正しく転送</span><span class="sxs-lookup"><span data-stu-id="e5b6e-102">Tracks number of chunks transferred correctly</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DirectoriesTransferred">
      <MemberSignature Language="C#" Value="public long DirectoriesTransferred;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 DirectoriesTransferred" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.DirectoriesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public DirectoriesTransferred As Long " />
      <MemberSignature Language="F#" Value="val mutable DirectoriesTransferred : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.DirectoriesTransferred" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-103">空のディレクトリのトラック数が正しく転送</span><span class="sxs-lookup"><span data-stu-id="e5b6e-103">Tracks number of empty directories transferred correctly</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntriesFailed">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus&gt; EntriesFailed;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.List`1&lt;class Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus&gt; EntriesFailed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.EntriesFailed" />
      <MemberSignature Language="VB.NET" Value="Public EntriesFailed As List(Of SingleEntryTransferStatus) " />
      <MemberSignature Language="F#" Value="val mutable EntriesFailed : System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus&gt;" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.EntriesFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.DataLake.Store.FileTransfer.SingleEntryTransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-104">ディレクトリまたはチャンクまたは正しく転送されなかった unchunked のファイルの一覧</span><span class="sxs-lookup"><span data-stu-id="e5b6e-104">List of directories or chunks or unchunked files that did not get transferred correctly</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntriesSkipped">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;string&gt; EntriesSkipped;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.HashSet`1&lt;string&gt; EntriesSkipped" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.EntriesSkipped" />
      <MemberSignature Language="VB.NET" Value="Public EntriesSkipped As HashSet(Of String) " />
      <MemberSignature Language="F#" Value="val mutable EntriesSkipped : System.Collections.Generic.HashSet&lt;string&gt;" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.EntriesSkipped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-105">既存のファイルを上書きしないためにスキップされるファイルの名前の一覧</span><span class="sxs-lookup"><span data-stu-id="e5b6e-105">List of name of files that are skipped because we did not want to overwrite existing files</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilesTransfered">
      <MemberSignature Language="C#" Value="public long FilesTransfered;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 FilesTransfered" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.FilesTransfered" />
      <MemberSignature Language="VB.NET" Value="Public FilesTransfered As Long " />
      <MemberSignature Language="F#" Value="val mutable FilesTransfered : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.FilesTransfered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-106">ファイルの数を追跡 (チャンクおよび unchunked を含む) は、正しく転送</span><span class="sxs-lookup"><span data-stu-id="e5b6e-106">Tracks number of files (includes chunked and unchunked) transferred correctly</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NonChunkedFileTransferred">
      <MemberSignature Language="C#" Value="public long NonChunkedFileTransferred;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 NonChunkedFileTransferred" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.NonChunkedFileTransferred" />
      <MemberSignature Language="VB.NET" Value="Public NonChunkedFileTransferred As Long " />
      <MemberSignature Language="F#" Value="val mutable NonChunkedFileTransferred : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.NonChunkedFileTransferred" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-107">転送されたトラック unchunked ファイル数</span><span class="sxs-lookup"><span data-stu-id="e5b6e-107">Tracks number of unchunked files transferred</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeTransfered">
      <MemberSignature Language="C#" Value="public long SizeTransfered;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 SizeTransfered" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.SizeTransfered" />
      <MemberSignature Language="VB.NET" Value="Public SizeTransfered As Long " />
      <MemberSignature Language="F#" Value="val mutable SizeTransfered : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.SizeTransfered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-108">チャンクのトラック数が正しく転送</span><span class="sxs-lookup"><span data-stu-id="e5b6e-108">Tracks number of chunks transferred correctly</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalChunksToTransfer">
      <MemberSignature Language="C#" Value="public long TotalChunksToTransfer;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 TotalChunksToTransfer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalChunksToTransfer" />
      <MemberSignature Language="VB.NET" Value="Public TotalChunksToTransfer As Long " />
      <MemberSignature Language="F#" Value="val mutable TotalChunksToTransfer : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalChunksToTransfer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-109">列挙体の後に転送する必要があるチャンクの合計数</span><span class="sxs-lookup"><span data-stu-id="e5b6e-109">Total number of chunks that needs to be transferred after enumeration</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalDirectoriesToTransfer">
      <MemberSignature Language="C#" Value="public long TotalDirectoriesToTransfer;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 TotalDirectoriesToTransfer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalDirectoriesToTransfer" />
      <MemberSignature Language="VB.NET" Value="Public TotalDirectoriesToTransfer As Long " />
      <MemberSignature Language="F#" Value="val mutable TotalDirectoriesToTransfer : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalDirectoriesToTransfer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-110">列挙体の後に転送する必要がある空のディレクトリの合計数</span><span class="sxs-lookup"><span data-stu-id="e5b6e-110">Total number of empty directories that needs to be transferred after enumeration</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFilesToTransfer">
      <MemberSignature Language="C#" Value="public long TotalFilesToTransfer;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 TotalFilesToTransfer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalFilesToTransfer" />
      <MemberSignature Language="VB.NET" Value="Public TotalFilesToTransfer As Long " />
      <MemberSignature Language="F#" Value="val mutable TotalFilesToTransfer : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalFilesToTransfer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-111">ファイルの合計数 (チャンクおよび unchunked を含む) 列挙型の後に転送する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5b6e-111">Total number of files (includes chunked and unchunked) that need to be transferred after enumeration</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalNonChunkedFileToTransfer">
      <MemberSignature Language="C#" Value="public long TotalNonChunkedFileToTransfer;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 TotalNonChunkedFileToTransfer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalNonChunkedFileToTransfer" />
      <MemberSignature Language="VB.NET" Value="Public TotalNonChunkedFileToTransfer As Long " />
      <MemberSignature Language="F#" Value="val mutable TotalNonChunkedFileToTransfer : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalNonChunkedFileToTransfer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-112">列挙体の後に転送する必要がある unchunked ファイルの合計数</span><span class="sxs-lookup"><span data-stu-id="e5b6e-112">Total number of unchunked files that needs to be transferred after enumeration</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalSizeToTransfer">
      <MemberSignature Language="C#" Value="public long TotalSizeToTransfer;" />
      <MemberSignature Language="ILAsm" Value=".field public int64 TotalSizeToTransfer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalSizeToTransfer" />
      <MemberSignature Language="VB.NET" Value="Public TotalSizeToTransfer As Long " />
      <MemberSignature Language="F#" Value="val mutable TotalSizeToTransfer : int64" Usage="Microsoft.Azure.DataLake.Store.FileTransfer.TransferStatus.TotalSizeToTransfer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5b6e-113">ファイルまたは列挙型の後に転送する必要があるチャンクの合計サイズ</span><span class="sxs-lookup"><span data-stu-id="e5b6e-113">Total size of files or chunks that need to be transferred after enumeration</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>