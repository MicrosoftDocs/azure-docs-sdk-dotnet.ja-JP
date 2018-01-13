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
            永続的ストレージにタスクまたはジョブの出力ファイルへの参照。
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
            基になるへの参照を取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />永続的ストレージにファイルを表すオブジェクト。 これは、blob のメソッドまたはには表示されませんのオーバー ロードを呼び出す使用できる、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.OutputFileReference" />抽象化します。
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
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            永続的なストレージからファイルを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
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
        <param name="target">対象のバイト配列。</param>
        <param name="index">バイト配列内の開始オフセット</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ファイルの内容をバイト配列にダウンロードします。
            </summary>
        <returns>バッファーに読み取られた合計バイト数。</returns>
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
        <param name="path">ファイルをダウンロードするためのパス。</param>
        <param name="mode">開くか、ファイルを作成する方法を指定します。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定されたパスにファイルの内容をダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
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
        <param name="target">対象のストリーム。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ファイルの内容をストリームにダウンロードします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
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
            ファイルが格納されているパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>ファイルは、ディレクトリのパスの下に格納された、FilePath プロパティは、基になる blob ストレージ (たとえば、mydirectory/myfile.txt) のディレクトリの区切り記号を使用します。 このようなパスは、Windows のパスとして直接使用できない可能性があります。</remarks>
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
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            永続的ストレージ内のファイルから読み取るのためのストリームを開きます。
            </summary>
        <returns>Blob からの読み取りに使用するストリーム。</returns>
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
            永続的ストレージ内のファイルの URI を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>