<Type Name="TransferParameters" FullName="Microsoft.Azure.Management.DataLake.Store.TransferParameters">
  <TypeSignature Language="C#" Value="public class TransferParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferParameters" />
  <TypeSignature Language="F#" Value="type TransferParameters = class" />
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
            DataLakeStoreTransferClient のパラメーターを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferParameters (string inputFilePath, string targetStreamPath, string accountName, int perFileThreadCount = -1, int concurrentFileCount = -1, bool isOverwrite = false, bool isResume = false, bool isBinary = true, bool isRecursive = false, bool isDownload = false, long maxSegmentLength = 268435456, string localMetadataLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string inputFilePath, string targetStreamPath, string accountName, int32 perFileThreadCount, int32 concurrentFileCount, bool isOverwrite, bool isResume, bool isBinary, bool isRecursive, bool isDownload, int64 maxSegmentLength, string localMetadataLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.TransferParameters.#ctor(System.String,System.String,System.String,System.Int32,System.Int32,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Boolean,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inputFilePath As String, targetStreamPath As String, accountName As String, Optional perFileThreadCount As Integer = -1, Optional concurrentFileCount As Integer = -1, Optional isOverwrite As Boolean = false, Optional isResume As Boolean = false, Optional isBinary As Boolean = true, Optional isRecursive As Boolean = false, Optional isDownload As Boolean = false, Optional maxSegmentLength As Long = 268435456, Optional localMetadataLocation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.TransferParameters : string * string * string * int * int * bool * bool * bool * bool * bool * int64 * string -&gt; Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="new Microsoft.Azure.Management.DataLake.Store.TransferParameters (inputFilePath, targetStreamPath, accountName, perFileThreadCount, concurrentFileCount, isOverwrite, isResume, isBinary, isRecursive, isDownload, maxSegmentLength, localMetadataLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inputFilePath" Type="System.String" />
        <Parameter Name="targetStreamPath" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="perFileThreadCount" Type="System.Int32" />
        <Parameter Name="concurrentFileCount" Type="System.Int32" />
        <Parameter Name="isOverwrite" Type="System.Boolean" />
        <Parameter Name="isResume" Type="System.Boolean" />
        <Parameter Name="isBinary" Type="System.Boolean" />
        <Parameter Name="isRecursive" Type="System.Boolean" />
        <Parameter Name="isDownload" Type="System.Boolean" />
        <Parameter Name="maxSegmentLength" Type="System.Int64" />
        <Parameter Name="localMetadataLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputFilePath">ファイルまたは転送されるフォルダーへの完全パス。</param>
        <param name="targetStreamPath">ここで、ファイルまたはフォルダーに転送されますストリームの完全パスです。</param>
        <param name="accountName">転送するアカウントの名前。</param>
        <param name="perFileThreadCount">あたりファイル スレッドの数、並列で転送するファイル セグメントの数を示すです。 この番号は、最適なパフォーマンスを FILE_SIZE/maxSegmentLength に制限されます。</param>
        <param name="concurrentFileCount">並列ファイルの数、フォルダーの転送中に同時に転送するファイルの数を示すです。 1 つのファイル転送では、このパラメーターは無視されます。 既定値はフォルダーを転送するための 5</param>
        <param name="isOverwrite">(省略可能)ターゲット ストリームを上書きするかどうか。</param>
        <param name="isResume">(省略可能)中断された転送を再開するかどうかを示します。</param>
        <param name="isBinary">(省略可能)入力ファイルをバイナリ ファイル (true) として扱うかどうか、またはレコード境界 (false) に転送のブロックを配置するかどうかを示します。</param>
        <param name="isRecursive">(省略可能)再帰的にソース フォルダーを転送するかどうかを示します。 True の場合、ソース ディレクトリを転送し、すべてのディレクトリの場合、ディレクトリ構造を保持します。</param>
        <param name="isDownload">設定した場合 (省略可能) <c>true</c> [はダウンロード] 転送シナリオではなくです。 既定値は false です。</param>
        <param name="maxSegmentLength">各セグメントの最大長。 既定では 256 mb で、最適なパフォーマンスが得られます。 ご自身の責任に変更します。</param>
        <param name="localMetadataLocation">(省略可能)ディレクトリ パスを移行が進行中に、ローカルの転送のメタデータ ファイルを格納する場所を示します。 この場所は、このアプリケーションから書き込み可能である必要があります。 既定の場所: SpecialFolder.LocalApplicationData です。</param>
        <summary>
            DataLakeStoreTransferClient を一連のパラメーターを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            転送、またはからダウンロードするアカウントの名前を示す値を取得します。
            </summary>
        <value>
            アカウントの名前です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentFileCount">
      <MemberSignature Language="C#" Value="public int ConcurrentFileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConcurrentFileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentFileCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ConcurrentFileCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.ConcurrentFileCount" />
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
            フォルダーにファイルの数が転送されるか、並列でダウンロードを示している並列ファイルの数を取得します。
            </summary>
        <value>
            ファイルを転送または同時ダウンロード数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
    <Member MemberName="FileEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding FileEncoding { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding FileEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.FileEncoding : System.Text.Encoding" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.FileEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            転送中のファイルのエンコードを示す値を取得します。
            </summary>
        <value>
            ファイルのエンコーディング。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputFilePath">
      <MemberSignature Language="C#" Value="public string InputFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InputFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InputFilePath As String" />
      <MemberSignature Language="F#" Value="member this.InputFilePath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.InputFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルまたは転送されるフォルダーへの完全パスを示す値を取得します。
            </summary>
        <value>
            入力ファイルのパス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBinary">
      <MemberSignature Language="C#" Value="public bool IsBinary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBinary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBinary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBinary : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsBinary" />
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
            入力ファイルをバイナリ (true) または区切られた入力 (false) として扱うかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>このインスタンスは、バイナリ、それ以外の場合<c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDownload">
      <MemberSignature Language="C#" Value="public bool IsDownload { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDownload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDownload As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDownload : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsDownload" />
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
            このインスタンスが転送ではなく、ローカル コンピューターにダウンロードするかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスがダウンロードされます。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOverwrite">
      <MemberSignature Language="C#" Value="public bool IsOverwrite { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOverwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOverwrite As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOverwrite : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsOverwrite" />
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
            既に存在する場合は、対象のストリームを上書きするかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスが上書きされます。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRecursive">
      <MemberSignature Language="C#" Value="public bool IsRecursive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRecursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRecursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRecursive : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsRecursive" />
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
            フォルダーの転送元フォルダーの再帰的に転送するかどうかを示す値を取得します。 これはフォルダーを転送するために有効ではのみであり、ファイル転送は無視されます。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスが再帰的です。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsResume">
      <MemberSignature Language="C#" Value="public bool IsResume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsResume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsResume As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsResume : bool" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.IsResume" />
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
            中断された転送を再開するかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>場合、このインスタンスが再開されます。 それ以外の場合、 <c>false</c>です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMetadataLocation">
      <MemberSignature Language="C#" Value="public string LocalMetadataLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalMetadataLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalMetadataLocation As String" />
      <MemberSignature Language="F#" Value="member this.LocalMetadataLocation : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.LocalMetadataLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ディレクトリ パスを転送用のメタデータを格納する場所を示す値を取得します。
            </summary>
        <value>
            ローカルのメタデータの場所です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSegementLength">
      <MemberSignature Language="C#" Value="public long MaxSegementLength { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSegementLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSegementLength As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSegementLength : int64" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.MaxSegementLength" />
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
            各セグメントの最大長を取得します。
            </summary>
        <value>
            各セグメントの最大長。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerFileThreadCount">
      <MemberSignature Language="C#" Value="public int PerFileThreadCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PerFileThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PerFileThreadCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PerFileThreadCount : int" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.PerFileThreadCount" />
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
            1 つのファイル転送を使用してまたはダウンロードする並列スレッドの最大数を示す値を取得します。
            </summary>
        <value>
            ファイルのスレッド数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetStreamPath">
      <MemberSignature Language="C#" Value="public string TargetStreamPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetStreamPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetStreamPath As String" />
      <MemberSignature Language="F#" Value="member this.TargetStreamPath : string" Usage="Microsoft.Azure.Management.DataLake.Store.TransferParameters.TargetStreamPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルに転送するストリームの完全パスを示す値を取得します。
            </summary>
        <value>
            ターゲット ストリーム パス。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>