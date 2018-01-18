<Type Name="FileToStage" FullName="Microsoft.Azure.Batch.FileStaging.FileToStage">
  <TypeSignature Language="C#" Value="public sealed class FileToStage : Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileToStage extends System.Object implements class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.FileToStage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileToStage&#xA;Implements IFileStagingProvider" />
  <TypeSignature Language="F#" Value="type FileToStage = class&#xA;    interface IFileStagingProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.FileStaging.IFileStagingProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2654a-101">Blob ストレージへのローカル ファイルのファイルのステージングを提供します。</span><span class="sxs-lookup"><span data-stu-id="2654a-101">Provides for file staging of a local file to blob storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileToStage (string localFileToStage, Microsoft.Azure.Batch.FileStaging.StagingStorageAccount storageCredentials, string nodeFileName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localFileToStage, class Microsoft.Azure.Batch.FileStaging.StagingStorageAccount storageCredentials, string nodeFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.#ctor(System.String,Microsoft.Azure.Batch.FileStaging.StagingStorageAccount,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (localFileToStage As String, storageCredentials As StagingStorageAccount, Optional nodeFileName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.FileStaging.FileToStage : string * Microsoft.Azure.Batch.FileStaging.StagingStorageAccount * string -&gt; Microsoft.Azure.Batch.FileStaging.FileToStage" Usage="new Microsoft.Azure.Batch.FileStaging.FileToStage (localFileToStage, storageCredentials, nodeFileName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="localFileToStage" Type="System.String" />
        <Parameter Name="storageCredentials" Type="Microsoft.Azure.Batch.FileStaging.StagingStorageAccount" />
        <Parameter Name="nodeFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="localFileToStage"><span data-ttu-id="2654a-102">ローカル ファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="2654a-102">The name of the local file.</span></span></param>
        <param name="storageCredentials"><span data-ttu-id="2654a-103">既定のコンテナーを作成するときに使用されるストレージの資格情報。</span><span class="sxs-lookup"><span data-stu-id="2654a-103">The storage credentials to be used when creating the default container.</span></span></param>
        <param name="nodeFileName"><span data-ttu-id="2654a-104">コンピューティング ノード上のファイルに指定する省略可能な名前です。</span><span class="sxs-lookup"><span data-stu-id="2654a-104">Optional name to be given to the file on the compute node.</span></span>  <span data-ttu-id="2654a-105">このパラメーターが null または存在しない場合、コンピューティング ノード上の名前は、すべてのパス情報を削除した localFileToStage の値に設定されます。</span><span class="sxs-lookup"><span data-stu-id="2654a-105">If this parameter is null or missing the name on the compute node will be set to the value of localFileToStage stripped of all path information.</span></span></param>
        <summary>
            <span data-ttu-id="2654a-106">ローカル ファイルを blob ストレージにステージングする必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="2654a-106">Specifies that a local file should be staged to blob storage.</span></span>  
            <span data-ttu-id="2654a-107">ストレージのコストには、指定されたアカウントが課金されます。</span><span class="sxs-lookup"><span data-stu-id="2654a-107">The specified account will be charged for storage costs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStagingArtifact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.CreateStagingArtifact" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateStagingArtifact () As IFileStagingArtifact" />
      <MemberSignature Language="F#" Value="abstract member CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact&#xA;override this.CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact" Usage="fileToStage.CreateStagingArtifact " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IFileStagingArtifact</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2654a-108">以下を参照してください。<see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact" /></span><span class="sxs-lookup"><span data-stu-id="2654a-108">See <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2654a-109">既定値を持つ IFileStagingArtifact のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2654a-109">An instance of IFileStagingArtifact with default values.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2654a-110">例外は、存在する場合、このファイルを段階的にしているときにキャッチします。</span><span class="sxs-lookup"><span data-stu-id="2654a-110">The exception, if any, caught while attempting to stage this file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalFileToStage">
      <MemberSignature Language="C#" Value="public string LocalFileToStage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalFileToStage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.LocalFileToStage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalFileToStage As String" />
      <MemberSignature Language="F#" Value="member this.LocalFileToStage : string" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.LocalFileToStage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2654a-111">Blob ストレージにステージングするローカル ファイルの名前</span><span class="sxs-lookup"><span data-stu-id="2654a-111">The name of the local file to stage to blob storage</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeFileName">
      <MemberSignature Language="C#" Value="public string NodeFileName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeFileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.NodeFileName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeFileName As String" />
      <MemberSignature Language="F#" Value="member this.NodeFileName : string" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.NodeFileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2654a-112">ターゲット ファイル名、コンピューティング ノードで、blob の内容をダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="2654a-112">The target filename, on the compute node, to which the blob contents will be downloaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagedFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.FileToStage.StagedFiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StagedFiles As IEnumerable(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.StagedFiles : seq&lt;Microsoft.Azure.Batch.ResourceFile&gt;" Usage="Microsoft.Azure.Batch.FileStaging.FileToStage.StagedFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2654a-113">ResourcesFile のステージのローカル ファイル用のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2654a-113">The instances of ResourcesFile for the staged local file.</span></span>
            <span data-ttu-id="2654a-114">この実装の 1 つのエントリがコレクションにこのオブジェクトの正常なファイル ステージングが発生します。</span><span class="sxs-lookup"><span data-stu-id="2654a-114">For this implementation, successful file staging of this object will result in a collection with only one entry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFilesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StageFilesAsync (System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StageFilesAsync(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, class Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFilesAsync (filesToStage As List(Of IFileStagingProvider), fileStagingArtifact As IFileStagingArtifact) As Task" />
      <MemberSignature Language="F#" Value="abstract member StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task&#xA;override this.StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task" Usage="fileToStage.StageFilesAsync (filesToStage, fileStagingArtifact)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.FileStaging.FileToStage/&lt;StageFilesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filesToStage" Type="System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt;" />
        <Parameter Name="fileStagingArtifact" Type="Microsoft.Azure.Batch.IFileStagingArtifact" />
      </Parameters>
      <Docs>
        <param name="filesToStage"><span data-ttu-id="2654a-115">ステージに IFileStagingProvider のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2654a-115">The instances of IFileStagingProvider to stage.</span></span></param>
        <param name="fileStagingArtifact"><span data-ttu-id="2654a-116">特定のエラー/進捗状況を含む成果物をステージング IFileStagingProvider です。</span><span class="sxs-lookup"><span data-stu-id="2654a-116">IFileStagingProvider specific staging artifacts including error/progress.</span></span></param>
        <summary>
            <span data-ttu-id="2654a-117">以下を参照してください。<see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" /></span><span class="sxs-lookup"><span data-stu-id="2654a-117">See <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="2654a-118">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2654a-118">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.FileToStage.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileToStage.Validate " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2654a-119">以下を参照してください。<see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate" /></span><span class="sxs-lookup"><span data-stu-id="2654a-119">See <see cref="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>