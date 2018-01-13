<Type Name="TransferSegmentMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata">
  <TypeSignature Language="C#" Value="public class TransferSegmentMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferSegmentMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferSegmentMetadata" />
  <TypeSignature Language="F#" Value="type TransferSegmentMetadata = class" />
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
      <AttributeName>System.Diagnostics.DebuggerDisplay("Segment {SegmentNumber}, Length = {Length}, Status = {Status}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            特定のファイル セグメントのメタデータを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CalculateSegmentCount">
      <MemberSignature Language="C#" Value="public static int CalculateSegmentCount (long fileLength);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 CalculateSegmentCount(int64 fileLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentCount(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CalculateSegmentCount (fileLength As Long) As Integer" />
      <MemberSignature Language="F#" Value="static member CalculateSegmentCount : int64 -&gt; int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentCount fileLength" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileLength" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fileLength">ファイルの長さをバイト単位で返します。</param>
        <summary>
            指定された長さのファイルを分割する必要があるセグメントの数を計算します。
            これを計算する方法は、両方のセグメントの数や入力ファイルのサイズが大きくなるにつれて、各セグメントの長さにするいくつかの経験的測定に基づいています。
            ファイルの長さが増えると対数パターン上で、どちらも拡大されます。
            数式は、約
            * 乗数 = Min (100, 50 * 2 ^ Log10(FileLengthInGB))
            * SegmentCount = Max (1, 乗数 * 2 ^ Log10(FileLengthInGB) 本質的には、数は 4 つのセグメントを各特定キャップを持つ、ファイルの長さが 10 倍に増加します。 数式は、小さなファイルと非常に大きなファイルの両方をサポート (およびが非常に小規模のセグメントの長さまたはセグメント数が非常に大きなされない) に設計されています。
            </summary>
        <returns>
            ファイルを分割するセグメントの数。 FileLength が 0 の場合は、0 を返します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">ファイルの長さを負の値にすることはできません。</exception>
      </Docs>
    </Member>
    <Member MemberName="CalculateSegmentLength">
      <MemberSignature Language="C#" Value="public static long CalculateSegmentLength (long fileLength, int segmentCount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int64 CalculateSegmentLength(int64 fileLength, int32 segmentCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentLength(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CalculateSegmentLength (fileLength As Long, segmentCount As Integer) As Long" />
      <MemberSignature Language="F#" Value="static member CalculateSegmentLength : int64 * int -&gt; int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.CalculateSegmentLength (fileLength, segmentCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileLength" Type="System.Int64" />
        <Parameter Name="segmentCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fileLength">ファイルの長さをバイト単位で返します。</param>
        <param name="segmentCount">ファイルを分割するセグメントの数。</param>
        <summary>
            指定された数のセグメントに分割されている指定された長さのファイルの一般的な (非終端) セグメントの長さを計算します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">セグメントの数は正の整数を指定する必要があります。</exception>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Length" />
      <MemberSignature Language="VB.NET" Value="Public Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (バイト単位) のセグメントのサイズを示す値を設定します。
            </summary>
        <value>
            長さ。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public long Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As Long" />
      <MemberSignature Language="F#" Value="member this.Offset : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Offset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルのセグメントの開始オフセットを示す値を設定します。
            </summary>
        <value>
            オフセット。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのセグメントに割り当てられているストリーム パスを示す値を設定します。
            </summary>
        <value>
            パス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentNumber">
      <MemberSignature Language="C#" Value="public int SegmentNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.SegmentNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentNumber As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentNumber : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.SegmentNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Number")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルのセグメントの数 (シーケンス) を示す値を設定します。
            </summary>
        <value>
            セグメントの数です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As SegmentTransferStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのセグメントの現在のアップロードのステータスを示す値を設定します。
            </summary>
        <value>
            ステータス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>