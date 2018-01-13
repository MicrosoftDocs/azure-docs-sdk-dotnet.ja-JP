<Type Name="IFileStagingProvider" FullName="Microsoft.Azure.Batch.FileStaging.IFileStagingProvider">
  <TypeSignature Language="C#" Value="public interface IFileStagingProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileStagingProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileStagingProvider" />
  <TypeSignature Language="F#" Value="type IFileStagingProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            基本的なファイルがステージング機能を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateStagingArtifact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IFileStagingArtifact CreateStagingArtifact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.CreateStagingArtifact" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateStagingArtifact () As IFileStagingArtifact" />
      <MemberSignature Language="F#" Value="abstract member CreateStagingArtifact : unit -&gt; Microsoft.Azure.Batch.IFileStagingArtifact" Usage="iFileStagingProvider.CreateStagingArtifact " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IFileStagingArtifact</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            返します。 任意の値の実装を持つ IFileStagingArtifact のインスタンスが必要です。
            これは、ステージングの成果物がそれ以外の場合に指定されていないときにファイルがステージング中に呼び出されます。
            </summary>
        <returns>どのような値を持つ IFileStagingArtifact のインスタンス、実装が必要です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StagedFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; StagedFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StagedFiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StagedFiles As IEnumerable(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.StagedFiles : seq&lt;Microsoft.Azure.Batch.ResourceFile&gt;" Usage="Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StagedFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル ステージングの結果である・ リソースファイル オブジェクトのコレクション。   
            IFileStagingProvider.StageFilesAsync() メソッドで設定する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageFilesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StageFilesAsync (System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StageFilesAsync(class System.Collections.Generic.List`1&lt;class Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; filesToStage, class Microsoft.Azure.Batch.IFileStagingArtifact fileStagingArtifact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.StageFilesAsync(System.Collections.Generic.List{Microsoft.Azure.Batch.FileStaging.IFileStagingProvider},Microsoft.Azure.Batch.IFileStagingArtifact)" />
      <MemberSignature Language="VB.NET" Value="Public Function StageFilesAsync (filesToStage As List(Of IFileStagingProvider), fileStagingArtifact As IFileStagingArtifact) As Task" />
      <MemberSignature Language="F#" Value="abstract member StageFilesAsync : System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt; * Microsoft.Azure.Batch.IFileStagingArtifact -&gt; System.Threading.Tasks.Task" Usage="iFileStagingProvider.StageFilesAsync (filesToStage, fileStagingArtifact)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filesToStage" Type="System.Collections.Generic.List&lt;Microsoft.Azure.Batch.FileStaging.IFileStagingProvider&gt;" />
        <Parameter Name="fileStagingArtifact" Type="Microsoft.Azure.Batch.IFileStagingArtifact" />
      </Parameters>
      <Docs>
        <param name="filesToStage">ステージングするのには、すべてのファイル ステージング オブジェクトのコレクションです。  すべてのインスタンスは、同じ実装型である必要があります。</param>
        <param name="fileStagingArtifact">特定のエラー/進捗状況を含む成果物をステージング IFileStagingProvider です。</param>
        <summary>
            指定したコレクション内のファイルのすべてをステージする非同期操作を開始します。
            ファイル ステージングの開始時に IFileStagingProvider のすべてのインスタンスはその実装の型によって bucketized です。
            これには、実装ごとにインスタンスの 1 つのコレクションが生成されます。
            IFileStagingProvider の各実装では、StageFilesAsync() メソッドがあります。  そのメソッドは、上記の bucketization 手順 oulined によって生成されたコレクションで 1 回呼び出されます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit" Usage="iFileStagingProvider.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のオブジェクトをクライアント側の検証を実行します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>