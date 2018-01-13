<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class&#xA;    interface ITransportObjectProvider&lt;ResourceFile&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            タスクの実行可能ファイルなど、コンピューティング ノードを Azure Blob ストレージからダウンロードし、タスクのファイルは、データ ファイルを入力します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.ResourceFile" Usage="new Microsoft.Azure.Batch.ResourceFile (blobSource, filePath, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobSource" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobSource">Azure Blob ストレージ内でのファイルの URL です。</param>
        <param name="filePath">タスクの作業ディレクトリに対して相対的、ファイルをダウンロードする場所です。</param>
        <param name="fileMode">8 進数形式でファイルのアクセス許可モード属性です。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.ResourceFile" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string" Usage="Microsoft.Azure.Batch.ResourceFile.BlobSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Blob ストレージ内でのファイルの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Blob はパブリックに読み取ることができない場合、この URL は、共有アクセス署名を含める必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string" Usage="Microsoft.Azure.Batch.ResourceFile.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            8 進数形式でファイルのアクセス許可モード属性を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>このプロパティは、リソース ファイルは、Linux ノードにダウンロードする場合にのみ適用されます。 指定されている場合、このプロパティは無視されます、<see cref="T:Microsoft.Azure.Batch.ResourceFile" />を Windows ノードにダウンロードされます。 このプロパティは指定しない場合、Linux ノードに対して、既定値は 0770 します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Batch.ResourceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクの作業ディレクトリに対して相対的、ファイルをダウンロードする場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>