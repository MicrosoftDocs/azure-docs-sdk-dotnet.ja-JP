<Type Name="IFileStagingArtifact" FullName="Microsoft.Azure.Batch.IFileStagingArtifact">
  <TypeSignature Language="C#" Value="public interface IFileStagingArtifact" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileStagingArtifact" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IFileStagingArtifact" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileStagingArtifact" />
  <TypeSignature Language="F#" Value="type IFileStagingArtifact = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ステージング処理ファイルに関する情報が含まれています。  ファイル ステージングは、通常の実行、 <see cref="T:Microsoft.Azure.Batch.CloudTask" /> (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            </summary>
    <remarks>
      <para>
            IFileStagingArtifact により、アプリケーションをカスタマイズして、ファイルをアップロード、クラウドでは、たとえば、タスク関連の操作の一部としてなど、プロセスに関する情報を取得する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>または<see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)">CloudJob.AddTaskAsync</see>です。  アプリケーションは、この情報を使用して、たとえば、Azure ストレージにアップロード プロセスの一部として作成されたコンテナーが情報を入手することがあります。
            </para>
      <para>
            ときに<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>が呼び出されると、コレクションのサービスのバッチに作業バッチのクライアントが送信されます。  バッチ クライアントがそのコレクションに対してファイルのステージングを実行する各コレクションを処理すると、: いずれかを指定ようなかどうかに表示するタスクを調べます<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />、され、その場合、ディクショナリ エントリの種類ごとに<see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />FilesToStage コレクション。 ディクショナリ エントリのキーは、<see cref="T:System.Type" />値と、IFileStagingProvider は IFileStagingArtifact の対応する実装のインスタンス。  たとえば、FilesToStage には、1 つ以上の FileToStage オブジェクト (Microsoft.Azure.Batch.FileStaging ライブラリから) が含まれている場合、ディクショナリに含まれるキーを持つ typeof(FileToStage) は、その値のインスタンスのエントリSequentialFileStagingArtifact です。
            </para>
      <para>
            タスクの追加操作が完了したら、またはアプリケーションがマルチ スレッドの場合、タスクの追加操作中に、ディクショナリを確認し、各 IFileStagingArtifact を型固有の情報を取得する適切な型に変換できます。  たとえば、タスクの追加操作には、1 つまたは複数の FileToStage オブジェクトが指定されている場合、typeof(FileToStage) によってキー指定された辞書エントリが見つかりません、SequentialFileStagingArtifact に値をキャストして調査できます、SequentialFileStagingArtifact.BlobContainerCreated プロパティのアップロード プロセスは、Azure ストレージに blob コンテナーを作成し、その場合はそのコンテナーの名前。
            この例は、自動的に作成されたコンテナーのクリーンアップに役立つ可能性があります。
            </para>
      <para>
            (単一タスクの追加のタスクの操作でも同様、点を除いて、複数のタスクのタスクの追加操作で、各タスクのコレクションの辞書がおよびで収集されます辞書、<see cref="T:System.Collections.Concurrent.ConcurrentBag`1" />単一タスクのタスクの追加操作であるだけに対して、。1 つのディクショナリ)。
            </para>
      <para>
            単一タスクのタスクの追加操作でファイルを事前設定することで適切なエントリでステージング処理をカスタマイズするのにディクショナリを使用することもできます。  たとえば、制御する、 <see cref="P:Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" /> FileToStage オブジェクトのグループにします。  使用してディクショナリを初期化できますし、 <c>{typeof(FileToStage)、新しい SequentialFileStagingArtifact {NamingFragment ="myname"}}</c> AddTaskAsync に渡す前にします。  IFileStagingProvider の FileToStage 実装には、独自に作成する代わりに、SequentialFileStagingArtifact し、使用します。  (この機能は複数のタスクのタスクの追加操作で使用できません) です。
            </para>
      <para>
            カスタムを開発している場合にも IFileStagingArtifact が発生する可能性があります<see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />です。
            ここでは実装に固有の情報を報告する IFileStagingArtifact のカスタム実装には、ステージング処理は、ファイルは通常作成します。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="NamingFragment">
      <MemberSignature Language="C#" Value="public string NamingFragment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamingFragment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" />
      <MemberSignature Language="VB.NET" Value="Public Property NamingFragment As String" />
      <MemberSignature Language="F#" Value="member this.NamingFragment : string with get, set" Usage="Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" />
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
            取得または既定の名前を構築するときに使用できる名前フラグメントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>呼び出し元は、このプロパティを設定可能性がありますが、<see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />実装は、これを考慮する必要はありません。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>