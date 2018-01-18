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
            <span data-ttu-id="897fc-101">Azure blob ストレージ コンテナー内のファイルのアップロード先を指定します。</span><span class="sxs-lookup"><span data-stu-id="897fc-101">Specifies a file upload destination within an Azure blob storage container.</span></span>
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
        <param name="containerUrl"><span data-ttu-id="897fc-102">ファイルをアップロードするには、Azure Blob ストレージ内のコンテナーの URL です。</span><span class="sxs-lookup"><span data-stu-id="897fc-102">The URL of the container within Azure Blob Storage to which to upload the file(s).</span></span></param>
        <param name="path"><span data-ttu-id="897fc-103">コピー先 blob またはファイルのアップロードをする Azure ストレージ コンテナー内の仮想ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="897fc-103">The destination blob or virtual directory within the Azure Storage container to which to upload the file(s).</span></span></param>
        <summary>
            <span data-ttu-id="897fc-104"><see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="897fc-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" /> class.</span></span>
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
            <span data-ttu-id="897fc-105">ファイルをアップロードするには、Azure Blob ストレージ内のコンテナーの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="897fc-105">Gets the URL of the container within Azure Blob Storage to which to upload the file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="897fc-106">URL は、Shared Access Signature (SAS)、コンテナーに対する書き込みアクセス許可の付与を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="897fc-106">The URL must include a Shared Access Signature (SAS) granting write permissions to the container.</span></span>
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
            <span data-ttu-id="897fc-107">コピー先 blob またはファイルのアップロードをする Azure ストレージ コンテナー内の仮想ディレクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="897fc-107">Gets the destination blob or virtual directory within the Azure Storage container to which to upload the file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="897fc-108">場合<see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />これをそのファイルをアップロードする blob の名前は、特定のファイル (つまりが含まれていないワイルドカード) を参照します。</span><span class="sxs-lookup"><span data-stu-id="897fc-108">If <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> refers to a specific file (i.e. it contains no wildcards), then this is the name of the blob to which to upload that file.</span></span></para>
          <para><span data-ttu-id="897fc-109">場合<see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />ワイルドカードが含まれています (および、したがって複数のファイルが一致する可能性があります)、し、このこれ (これは、各 blob の名前に付加される) blob の仮想ディレクトリの名前をファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="897fc-109">If <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> contains wildcards (and may therefore match multiple files), then this then this is the name of the blob virtual directory (which is prepended to each blob name) to which to upload the file(s).</span></span></para>
          <para><span data-ttu-id="897fc-110">省略した場合、そのファイル名と一致する blob 名前コンテナーのルートにファイルがアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="897fc-110">If omitted, file(s) are uploaded to the root of the container with a blob name matching their file name.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>