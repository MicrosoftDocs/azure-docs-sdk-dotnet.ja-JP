<Type Name="CloudJobExtensions" FullName="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions">
  <TypeSignature Language="C#" Value="public static class CloudJobExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudJobExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudJobExtensions" />
  <TypeSignature Language="F#" Value="type CloudJobExtensions = class" />
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
            出力を操作するためのメソッドを提供する<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job">コンテナーを作成するジョブです。</param>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <summary>
            を含めた、Shared Access Signature (SAS) を Azure blob ストレージに、ジョブの出力のストレージ コンテナーの書き込みを可能にする URL を取得します。 この URL は、使用できるように、タスクに渡すに適した、<see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" />または<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />を受け取るコンス トラクター、<see cref="T:System.Uri" />です。
            </summary>
        <returns>ジョブ出力コンテナーの SAS を含む URL です。</returns>
        <remarks>SAS は、7 日後に期限が切れます。 この既定値はタスク アクティブなままにできる最長時間を一致するように選択されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, TimeSpan expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.TimeSpan expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount, expiryTime As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * TimeSpan -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount, expiryTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="expiryTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="job">コンテナーを作成するジョブです。</param>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <param name="expiryTime">SAS の有効期間です。  はず作成され、完了すると、エラーや再試行の余裕を含むを実行するジョブのすべてのタスクを許可するのに十分な長さです。</param>
        <summary>
            を含めた、Shared Access Signature (SAS) を Azure blob ストレージに、ジョブの出力のストレージ コンテナーの書き込みを可能にする URL を取得します。 この URL は、使用できるように、タスクに渡すに適した、<see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" />または<see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />を受け取るコンス トラクター、<see cref="T:System.Uri" />です。
            </summary>
        <returns>ジョブ出力コンテナーの SAS を含む URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorage (job As CloudJob, storageAccount As CloudStorageAccount) As JobOutputStorage" />
      <MemberSignature Language="F#" Value="static member OutputStorage : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job">記憶域の出力を取得するジョブです。</param>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />の指定された<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <returns>指定されたジョブの JobOutputStorage します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorageContainerName">
      <MemberSignature Language="C#" Value="public static string OutputStorageContainerName (this Microsoft.Azure.Batch.CloudJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string OutputStorageContainerName(class Microsoft.Azure.Batch.CloudJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName(Microsoft.Azure.Batch.CloudJob)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorageContainerName (job As CloudJob) As String" />
      <MemberSignature Language="F#" Value="static member OutputStorageContainerName : Microsoft.Azure.Batch.CloudJob -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
      </Parameters>
      <Docs>
        <param name="job">コンテナー名を取得するジョブです。</param>
        <summary>
            出力の Azure blob ストレージ コンテナーの名前を取得、<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <returns>このジョブの出力を保存するために、コンテナーの名前。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareOutputStorageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PrepareOutputStorageAsync (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PrepareOutputStorageAsync(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PrepareOutputStorageAsync : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync (job, storageAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions/&lt;PrepareOutputStorageAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job">コンテナーを作成するジョブです。</param>
        <param name="storageAccount">ストレージ アカウントは、Azure Batch アカウントにリンクします。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            出力用の Azure blob ストレージ コンテナーを作成、<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>