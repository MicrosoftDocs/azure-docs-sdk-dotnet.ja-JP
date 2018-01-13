<Type Name="SegmentTransferProgress" FullName="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress">
  <TypeSignature Language="C#" Value="public class SegmentTransferProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SegmentTransferProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress" />
  <TypeSignature Language="VB.NET" Value="Public Class SegmentTransferProgress" />
  <TypeSignature Language="F#" Value="type SegmentTransferProgress = class" />
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
            <span data-ttu-id="41134-101">セグメントに転送の進捗状況をレポートに使用されるクラスを表します。</span><span class="sxs-lookup"><span data-stu-id="41134-101">Represents a class used for reporting transfer progress on a segment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IsFailed">
      <MemberSignature Language="C#" Value="public bool IsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.IsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFailed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFailed : bool" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.IsFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="41134-102">転送が失敗したかどうかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="41134-102">Gets a value indicating whether the transfer failed or not.</span></span>
            </summary>
        <value>
          <span data-ttu-id="41134-103"><c>true</c>このインスタンスが失敗した、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="41134-103"><c>true</c> if this instance is failed; otherwise, <c>false</c>.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.Length" />
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
            <span data-ttu-id="41134-104">セグメントの長さ (バイト) を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="41134-104">Gets a value indicating the segment length, in bytes.</span></span>
            </summary>
        <value>
            <span data-ttu-id="41134-105">長さ。</span><span class="sxs-lookup"><span data-stu-id="41134-105">The length.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentNumber">
      <MemberSignature Language="C#" Value="public int SegmentNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.SegmentNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SegmentNumber As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentNumber : int" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.SegmentNumber" />
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
            <span data-ttu-id="41134-106">この進行状況レポートを指すセグメント数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="41134-106">Gets a value indicating the segment number this progress report refers to.</span></span>
            </summary>
        <value>
            <span data-ttu-id="41134-107">セグメントの数です。</span><span class="sxs-lookup"><span data-stu-id="41134-107">The segment number.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferredByteCount">
      <MemberSignature Language="C#" Value="public long TransferredByteCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferredByteCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.TransferredByteCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferredByteCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferredByteCount : int64" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferProgress.TransferredByteCount" />
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
            <span data-ttu-id="41134-108">このセグメントのこれまでに転送されたバイト数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="41134-108">Gets a value indicating the number of bytes transferred so far for this segment.</span></span>
            </summary>
        <value>
            <span data-ttu-id="41134-109">転送されたバイト数。</span><span class="sxs-lookup"><span data-stu-id="41134-109">The transferred byte count.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>