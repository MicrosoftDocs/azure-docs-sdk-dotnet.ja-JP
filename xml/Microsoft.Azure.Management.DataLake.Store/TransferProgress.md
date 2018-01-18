<Type Name="TransferProgress" FullName="Microsoft.Azure.Management.DataLake.Store.TransferProgress">
  <TypeSignature Language="C#" Value="public class TransferProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferProgress" />
  <TypeSignature Language="F#" Value="type TransferProgress = class" />
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
            <span data-ttu-id="6e5f1-101">転送時に進行状況を報告します。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-101">Reports progress on a transfer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSegmentProgress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress GetSegmentProgress (int segmentNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress GetSegmentProgress(int32 segmentNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferProgress.GetSegmentProgress(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSegmentProgress (segmentNumber As Integer) As SegmentTransferProgress" />
      <MemberSignature Language="F#" Value="member this.GetSegmentProgress : int -&gt; Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress" Usage="transferProgress.GetSegmentProgress segmentNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="segmentNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentNumber"><span data-ttu-id="6e5f1-102">情報を取得するセグメントのシーケンス番号</span><span class="sxs-lookup"><span data-stu-id="6e5f1-102">The sequence number of the segment to retrieve information for</span></span></param>
        <summary>
            <span data-ttu-id="6e5f1-103">特定のセグメントの転送の進捗状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-103">Gets the transfer progress for a particular segment.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFileLength">
      <MemberSignature Language="C#" Value="public long TotalFileLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalFileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalFileLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFileLength As Long" />
      <MemberSignature Language="F#" Value="member this.TotalFileLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalFileLength" />
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
            <span data-ttu-id="6e5f1-104">転送するファイルの合計の長さを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-104">Gets a value indicating the total length of the file to transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6e5f1-105">ファイルの合計の長さ。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-105">The total length of the file.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalSegmentCount">
      <MemberSignature Language="C#" Value="public int TotalSegmentCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TotalSegmentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalSegmentCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalSegmentCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TotalSegmentCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TotalSegmentCount" />
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
            <span data-ttu-id="6e5f1-106">転送するセグメントの合計数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-106">Gets a value indicating the total number of segments to transfer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6e5f1-107">セグメントの合計数。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-107">The total segment count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferProgress.TransferredByteCount" />
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
            <span data-ttu-id="6e5f1-108">これまでに転送されたバイト数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-108">Gets a value indicating the number of bytes that have been transferred so far.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6e5f1-109">転送されたバイト数。</span><span class="sxs-lookup"><span data-stu-id="6e5f1-109">The transferred byte count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>