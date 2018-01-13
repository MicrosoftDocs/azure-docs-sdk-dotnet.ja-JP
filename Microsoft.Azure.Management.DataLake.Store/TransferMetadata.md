<Type Name="TransferMetadata" FullName="Microsoft.Azure.Management.DataLake.Store.TransferMetadata">
  <TypeSignature Language="C#" Value="public class TransferMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferMetadata" />
  <TypeSignature Language="F#" Value="type TransferMetadata = class" />
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
      <AttributeName>System.Diagnostics.DebuggerDisplay("Segments = {SegmentCount}, SegmentLength = {SegmentLength}, TransferId = {TransferId}, FileLength = {FileLength}, FilePath = {FilePath}, EncodingCodePage = {EncodingCodePage}, Delimiter = {Delimiter}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            転送に関連する一般的なメタデータを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteFile">
      <MemberSignature Language="C#" Value="public void DeleteFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteFile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.DeleteFile" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteFile ()" />
      <MemberSignature Language="F#" Value="member this.DeleteFile : unit -&gt; unit" Usage="transferMetadata.DeleteFile " />
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
            メタデータ ファイルをディスクから削除します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Null または空の MetadataFilePath します。 このプロパティが設定されるまで、メタデータを削除することはできません。</exception>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Delimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合は、ファイルは、レコード境界区切りを示す値を取得します。
            </summary>
        <value>
            レコードの境界の区切り記号
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingCodePage">
      <MemberSignature Language="C#" Value="public int EncodingCodePage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 EncodingCodePage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.EncodingCodePage" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingCodePage As Integer" />
      <MemberSignature Language="F#" Value="member this.EncodingCodePage : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.EncodingCodePage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="EncodingCodePage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在のエンコーディングのコード ページは使用されているを取得します。
            </summary>
        <value>
             現在のエンコーディングのコード ページ。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileLength">
      <MemberSignature Language="C#" Value="public long FileLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FileLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.FileLength" />
      <MemberSignature Language="VB.NET" Value="Public Property FileLength As Long" />
      <MemberSignature Language="F#" Value="member this.FileLength : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.FileLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="FileLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または転送するファイルのバイト単位で長さを示す値を設定します。
            </summary>
        <value>
            ファイルの長さ。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="InputFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            /を取得または転送するファイルへの完全パスを示す値を設定します。
            </summary>
        <value>
            入力ファイルのパス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsBinary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsBinary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            か、バイナリ ファイルとして転送ファイルを処理するかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>このインスタンスは、バイナリ、それ以外の場合<c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.IsDownload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IsDownload")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのインスタンスが、転送ではなく、ダウンロードするかどうかを示す値を設定します。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスがダウンロードされます。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentCount">
      <MemberSignature Language="C#" Value="public int SegmentCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SegmentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SegmentCount : int with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのファイルは、セグメントの数に分割を転送中のためにそれを示す値を設定します。
            </summary>
        <value>
            セグメントの数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentLength">
      <MemberSignature Language="C#" Value="public long SegmentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SegmentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentLength As Long" />
      <MemberSignature Language="F#" Value="member this.SegmentLength : int64 with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (ただし、最後、少ない可能性があります)、ファイルの各セグメントの長さ (単位: バイト) を示す値を設定します。
            </summary>
        <value>
            セグメントの長さ。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Segments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] Segments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] Segments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Segments" />
      <MemberSignature Language="VB.NET" Value="Public Property Segments As TransferSegmentMetadata()" />
      <MemberSignature Language="F#" Value="member this.Segments : Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[] with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Segments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Segments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferSegmentMetadata[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            セグメントのメタデータの配列へのポインターを取得します。 セグメントは、それらのセグメント数 (シーケンス) で並べ替えられます。
            </summary>
        <value>
            セグメント。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SegmentStreamDirectory">
      <MemberSignature Language="C#" Value="public string SegmentStreamDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SegmentStreamDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentStreamDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property SegmentStreamDirectory As String" />
      <MemberSignature Language="F#" Value="member this.SegmentStreamDirectory : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.SegmentStreamDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="SegmentStreamDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または中間セグメント ストリームを保存するディレクトリ パスを示す値を設定します。
            </summary>
        <value>
            ターゲット ストリーム パス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As SegmentTransferStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.Status" />
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
            取得またはこのファイルの転送の現在の転送状態を示す値を設定します。
            この値は、フォルダーの転送の進捗状況と再開に対してチェックされます。 単一のファイル転送では、セグメントの状態を使用して、追跡します。
            </summary>
        <value>
            ステータス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetStreamPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイルに転送するストリームの完全パスを示す値を設定します。
            </summary>
        <value>
            ターゲット ストリーム パス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferId">
      <MemberSignature Language="C#" Value="public string TransferId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TransferId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TransferId" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferId As String" />
      <MemberSignature Language="F#" Value="member this.TransferId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.TransferMetadata.TransferId" />
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
            取得またはこの譲渡に関連付けられている一意の識別子を示す値を設定します。
            </summary>
        <value>
            転送の識別子です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>