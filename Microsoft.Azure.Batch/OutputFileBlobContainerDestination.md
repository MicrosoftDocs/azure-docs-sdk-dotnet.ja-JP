<Type Name="OutputFileBlobContainerDestination" FullName="Microsoft.Azure.Batch.OutputFileBlobContainerDestination">
  <TypeSignature Language="C#" Value="public class OutputFileBlobContainerDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileBlobContainerDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileBlobContainerDestination" />
  <TypeSignature Language="F#" Value="type OutputFileBlobContainerDestination = class&#xA;    interface ITransportObjectProvider&lt;OutputFileBlobContainerDestination&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Azure blob ストレージ コンテナー内のファイルのアップロード先を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination (string containerUrl, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerUrl, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerUrl As String, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination : string * string -&gt; Microsoft.Azure.Batch.OutputFileBlobContainerDestination" Usage="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination (containerUrl, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerUrl" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerUrl">ファイルをアップロードするには、Azure Blob ストレージ内のコンテナーの URL です。</param>
        <param name="path">コピー先 blob またはファイルのアップロードをする Azure ストレージ コンテナー内の仮想ディレクトリです。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerUrl">
      <MemberSignature Language="C#" Value="public string ContainerUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ContainerUrl : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
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
            ファイルをアップロードするには、Azure Blob ストレージ内のコンテナーの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            URL は、Shared Access Signature (SAS)、コンテナーに対する書き込みアクセス許可の付与を含める必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
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
            コピー先 blob またはファイルのアップロードをする Azure ストレージ コンテナー内の仮想ディレクトリを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>場合<see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />これをそのファイルをアップロードする blob の名前は、特定のファイル (つまりが含まれていないワイルドカード) を参照します。</para>
          <para>場合<see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />ワイルドカードが含まれています (および、したがって複数のファイルが一致する可能性があります)、し、このこれ (これは、各 blob の名前に付加される) blob の仮想ディレクトリの名前をファイルをアップロードします。</para>
          <para>省略した場合、そのファイル名と一致する blob 名前コンテナーのルートにファイルがアップロードされます。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>