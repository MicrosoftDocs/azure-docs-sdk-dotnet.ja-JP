<Type Name="TransferFolderProgress" FullName="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress">
  <TypeSignature Language="C#" Value="public class TransferFolderProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferFolderProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferFolderProgress" />
  <TypeSignature Language="F#" Value="type TransferFolderProgress = class" />
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
            <span data-ttu-id="b3acd-101">フォルダーの転送に関する進行状況を報告します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-101">Reports progress on an transfer for a folder.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedFileCount">
      <MemberSignature Language="C#" Value="public long FailedFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.FailedFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedFileCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedFileCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.FailedFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3acd-102">失敗したファイルの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-102">Gets the count of files that failed.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3acd-103">失敗したファイルの数。</span><span class="sxs-lookup"><span data-stu-id="b3acd-103">The failed file count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSegmentProgress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferProgress GetSegmentProgress (int segmentNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.DataLake.Store.TransferProgress GetSegmentProgress(int32 segmentNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.GetSegmentProgress(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSegmentProgress (segmentNumber As Integer) As TransferProgress" />
      <MemberSignature Language="F#" Value="member this.GetSegmentProgress : int -&gt; Microsoft.Azure.Management.DataLake.Store.TransferProgress" Usage="transferFolderProgress.GetSegmentProgress segmentNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferProgress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="segmentNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentNumber"><span data-ttu-id="b3acd-104">情報を取得するファイルのシーケンス番号</span><span class="sxs-lookup"><span data-stu-id="b3acd-104">The sequence number of the file to retrieve information for</span></span></param>
        <summary>
            <span data-ttu-id="b3acd-105">特定のファイルの転送の進捗状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-105">Gets the transfer progress for a particular file.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileCount">
      <MemberSignature Language="C#" Value="public int TotalFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TotalFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TotalFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3acd-106">ファイルの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-106">Gets the total file count.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3acd-107">ファイルの合計数。</span><span class="sxs-lookup"><span data-stu-id="b3acd-107">The total file count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileLength">
      <MemberSignature Language="C#" Value="public long TotalFileLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileLength As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TotalFileLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3acd-108">転送するファイルの合計の長さを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-108">Gets a value indicating the total length of the file to transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3acd-109">ファイルの合計の長さ。</span><span class="sxs-lookup"><span data-stu-id="b3acd-109">The total length of the file.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredByteCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3acd-110">これまでに転送されたバイト数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-110">Gets a value indicating the number of bytes that have been transferred so far.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3acd-111">転送されたバイト数。</span><span class="sxs-lookup"><span data-stu-id="b3acd-111">The transferred byte count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredFileCount">
      <MemberSignature Language="C#" Value="public long TransferredFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredFileCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredFileCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress.TransferredFileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3acd-112">転送されたファイルの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3acd-112">Gets the transferred file count.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b3acd-113">転送されたファイルの数。</span><span class="sxs-lookup"><span data-stu-id="b3acd-113">The transferred file count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>