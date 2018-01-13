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
            セグメントに転送の進捗状況をレポートに使用されるクラスを表します。
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
            転送が失敗したかどうかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>このインスタンスが失敗した、それ以外の場合<c>false</c>です。
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
            セグメントの長さ (バイト) を示す値を取得します。
            </summary>
        <value>
            長さ。
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
            この進行状況レポートを指すセグメント数を示す値を取得します。
            </summary>
        <value>
            セグメントの数です。
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
            このセグメントのこれまでに転送されたバイト数を示す値を取得します。
            </summary>
        <value>
            転送されたバイト数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>