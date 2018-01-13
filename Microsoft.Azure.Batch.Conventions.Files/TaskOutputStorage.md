<Type Name="TaskOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage">
  <TypeSignature Language="C#" Value="public class TaskOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskOutputStorage" />
  <TypeSignature Language="F#" Value="type TaskOutputStorage = class" />
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
            Azure Batch のタスクの出力の永続的な記憶域を表します。
            </summary>
    <remarks>
            タスクの出力は、ジョブ全体ではなく、特定のタスクに論理的に関連付けられている出力データを参照してください。 たとえば、ムービー レンダリング ジョブ、タスクが 1 つのフレームをレンダリングする場合そのフレームなりますタスクの出力。  ログと中間ファイルなどの他の診断情報も永続化タスクの出力として (を参照してください<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />クライアントは、メイン出力の補助的なデータと識別できるように、これらを分類する方法について)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">このジョブに関連付けられている出力に使用する Azure storage blob コンテナーの URL です。 この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</param>
        <param name="taskId">Azure Batch のタスクの id。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />タスク id と、ジョブ出力のコンテナーを表す URL からのクラスです。
            </summary>
        <remarks>コンテナーは既に存在する必要があります。TaskOutputStorage クラスが作成していないのです。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <param name="jobId">タスクを含む Azure Batch のジョブの id。</param>
        <param name="taskId">Azure Batch のタスクの id。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />クラスからストレージ アカウント、ジョブの id、およびタスクの id。
            </summary>
        <remarks>ジョブ出力コンテナーが存在する必要があります。TaskOutputStorage クラスが作成していないのです。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">このジョブに関連付けられている出力に使用する Azure storage blob コンテナーの URL です。 この URL は、コンテナーへのアクセスを付与する SAS (Shared Access Signature) を含める必要があります。 またはコンテナーをパブリックにする必要があります。</param>
        <param name="taskId">Azure Batch のタスクの id。</param>
        <param name="storageRetryPolicy">記憶域の要求の再試行ポリシーです。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />タスク id と、ジョブ出力のコンテナーを表す URL からのクラスです。
            </summary>
        <remarks>コンテナーは既に存在する必要があります。TaskOutputStorage クラスが作成していないのです。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <param name="jobId">タスクを含む Azure Batch のジョブの id。</param>
        <param name="taskId">Azure Batch のタスクの id。</param>
        <param name="storageRetryPolicy">記憶域の要求の再試行ポリシーです。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />クラスからストレージ アカウント、ジョブの id、およびタスクの id。
            </summary>
        <remarks>ジョブ出力コンテナーが存在する必要があります。TaskOutputStorage クラスが作成していないのです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;GetOutputAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />を取得する出力のカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <param name="filePath">Blob ストレージに永続化が出力されるパスです。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            種類とパスによって Azure blob ストレージからのタスクの出力を取得します。
            </summary>
        <returns>Azure blob ストレージに要求されたファイルへの参照。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As TaskOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />出力を一覧表示などのカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <summary>
            指定した種類のタスクの出力を一覧表示します。
            </summary>
        <returns>指定した種類の永続化されたタスク出力の一覧です。</returns>
        <remarks>列挙される場合に遅延の一覧を取得し、Azure blob ストレージからされます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <param name="relativePath">現在のディレクトリに対して相対的に、保存するファイルのパス。
            ファイルが現在のディレクトリのサブディレクトリ内にある場合は、相対パスは blob ストレージに保持されます。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したファイルを永続的ストレージに保存します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>ファイルが現在のディレクトリの外部にある場合は、ディレクトリ ツリーを走査は削除されます。
            たとえば、<paramref name="relativePath" />の"..\ProcessEnv.cmd"の blob 名を作成する目的で"ProcessEnv.cmd"として取り扱われます。</remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="kind" />または<paramref name="relativePath" />引数が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="relativePath" />引数が絶対パス、または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <param name="sourcePath">保存するファイルのパス。</param>
        <param name="destinationRelativePath">ファイルの保存先となる blob の名前です。 これには、"pointclouds/pointcloud_0001.txt"などの相対的なコンポーネントが含まれます。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したファイルを永続的ストレージに保存します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="kind" />、 <paramref name="sourcePath" />、または<paramref name="destinationRelativePath" />引数が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="sourcePath" />または<paramref name="destinationRelativePath" />引数が空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveTextAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveTextAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTextAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveTextAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveTextAsync (kind, text, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このデータの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <param name="text">保存するテキスト。</param>
        <param name="destinationRelativePath">テキストの保存に使用する blob の名前です。 これには、"records/widget42.json"などの相対的なコンポーネントが含まれます。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ローカル ファイルを作成することがなく、指定したテキストを永続的な記憶域に保存します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="kind" />、 <paramref name="text" />、または<paramref name="destinationRelativePath" />引数が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="destinationRelativePath" />引数が空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (string relativePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(string relativePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (relativePath As String) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync relativePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativePath">現在のディレクトリに対して相対的に、保存するファイルのパス。
            ファイルが現在のディレクトリのサブディレクトリ内にある場合は、相対パスは blob ストレージに保持されます。</param>
        <summary>
            永続的な記憶域に指定されたファイルを保存、 <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />、および後続のトラックがファイルに追加しても永続的なコピーに追加します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />ファイルを blob ストレージに保存され、ファイルを定期的にフラッシュが破棄されるまで、blob に追加します。  破棄されると、残りのすべて追加が blob ストレージ、さらにフラッシュされたファイルの追跡の追加が停止します。</returns>
        <remarks>
          <para>追跡のサポートのみ追加します。 つまり、ファイルが追跡されているときに最後に追加されたデータすべてが永続的ストレージに追加されます。 永続的なストアに既にアップロードされているデータへの変更は反映されません。 したがって、このメソッドはデータがファイルの末尾に追加のみ (非回転) ログ ファイルなどのファイルでのみ使用するためものです。
            ファイルの内容全体が変更できる場合を使用して<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />および定期的にまたはそれぞれの変更後の呼び出しです。</para>
          <para>ファイルが現在のディレクトリの外部にある場合は、ディレクトリ ツリーを走査は削除されます。
            たとえば、<paramref name="relativePath" />の"..\ProcessEnv.cmd"の blob 名を作成する目的で"ProcessEnv.cmd"として取り扱われます。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="relativePath" /> 引数が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="relativePath" />引数が絶対パス、または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, TimeSpan flushInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.TimeSpan flushInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (kind As TaskOutputKind, sourcePath As String, destinationRelativePath As String, flushInterval As TimeSpan) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync (kind, sourcePath, destinationRelativePath, flushInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="flushInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="kind">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />など、このファイルの格納に使用するカテゴリを表す<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />または<see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />です。</param>
        <param name="sourcePath">保存するファイルのパス。</param>
        <param name="destinationRelativePath">ファイルの保存先となる blob の名前です。 これには、"pointclouds/pointcloud_0001.txt"などの相対的なコンポーネントが含まれます。</param>
        <param name="flushInterval">フラッシュ間隔は、永続的な記憶域を追加します。</param>
        <summary>
            保存永続的な記憶域、および後続のトラックを指定したファイルはファイルに追加しても永続的なコピーに追加します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" />ファイルを blob ストレージに保存され、ファイルを定期的にフラッシュが破棄されるまで、blob に追加します。  破棄されると、残りのすべて追加が blob ストレージ、さらにフラッシュされたファイルの追跡の追加が停止します。</returns>
        <remarks>
          <para>追跡のサポートのみ追加します。 つまり、ファイルが追跡されているときに最後に追加されたデータすべてが永続的ストレージに追加されます。 永続的なストアに既にアップロードされているデータへの変更は反映されません。 したがって、このメソッドはデータがファイルの末尾に追加のみ (非回転) ログ ファイルなどのファイルでのみ使用するためものです。
            ファイルの内容全体が変更できる場合を使用して<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />および定期的にまたはそれぞれの変更後の呼び出しです。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="kind" />、 <paramref name="sourcePath" />、または<paramref name="destinationRelativePath" />引数が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="sourcePath" />または<paramref name="destinationRelativePath" />引数が空です。</exception>
      </Docs>
    </Member>
  </Members>
</Type>