<Type Name="JobReleaseTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask">
  <TypeSignature Language="C#" Value="public class JobReleaseTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTask" />
  <TypeSignature Language="F#" Value="type JobReleaseTask = class" />
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
            ジョブのリリース タスクをジョブを実行した任意のコンピューティング ノードでジョブの完了時に実行します。
            </summary>
    <remarks>
            ジョブのリリース タスクを実行、ジョブが終了すると、次のいずれかの理由: ユーザーを呼び出して終了ジョブ API、または削除ジョブ API ジョブがアクティブである、ジョブの最大のウォール クロック時間の制限に達すると、およびジョブがアクティブであるときに、または完了すると、ジョブのジョブ マネージャー タスクとジョブがジョブ マネージャーが完了したときに終了するように構成します。 ここで、ジョブのタスクが実行し、ジョブの準備タスクが実行され、完了した各コンピューティング ノードでジョブのリリース タスクが実行されます。 コンピューティング ノードをコンピューティング ノードが実行したジョブの準備タスクとジョブが、これ以上のタスクで実行されているジョブの終了後に再イメージ化する (そのため、ジョブの準備タスクが再実行されない) 場合、ジョブのリリース タスクが実行されないそのノード上。 場合は、コンピューティング ノードを再起動すると、ジョブのリリース タスクが実行中でも、コンピューティング ノードの起動時には、ジョブのリリース タスクが再度実行されます。 すべてのジョブのリリース タスクが完了するまで、ジョブは完了済みとしてマークされません。 ジョブのリリース タスクは、バック グラウンドで実行されます。 スケジュールのスロットを占有しませんつまり、プールに指定された maxTasksPerNode 上限に達するまではカウントされません。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobReleaseTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.Azure.Batch.Protocol.Models.UserIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity -&gt; Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, maxWallClockTime, retentionTime, userIdentity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
      </Parameters>
      <Docs>
        <param name="commandLine">ジョブのリリース タスクのコマンドラインです。</param>
        <param name="id">ジョブ内のジョブのリリース タスクを一意に識別する文字列。</param>
        <param name="containerSettings">ジョブのリリース タスクを実行するコンテナーの設定。</param>
        <param name="resourceFiles">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</param>
        <param name="environmentSettings">ジョブのリリース タスクに対する環境変数設定の一覧。</param>
        <param name="maxWallClockTime">ジョブのリリース タスクがタスクを実行時点から計測されます、特定のコンピューティング ノードで最大経過時間を開始します。 制限時間内にタスクが完了しない場合、Batch service によって終了します。 既定値は、15 分です。 15 分より長いタイムアウトを指定することはできません。 場合は、バッチ サービス拒否が次のエラーです。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</param>
        <param name="retentionTime">コンピューティング ノードでジョブのリリース タスクの作業ディレクトリを保持する最小期間。 この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。</param>
        <param name="userIdentity">ジョブのリリース タスクを実行するユーザー id。</param>
        <summary>
            JobReleaseTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクのコマンドラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。 このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクを実行するコンテナーの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクに対する環境変数設定の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ジョブ内のジョブのリリース タスクを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ID は、ハイフンとアンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。 このプロパティを指定しない場合、Batch service は、'jobrelease' の既定値を割り当てます。 ジョブ内の他のタスクがジョブのリリース タスクと同じ ID を持つことはできません。 同じ id を持つタスクを送信しようとすると、バッチ サービスはエラー コード TaskIdSameAsJobReleaseTask; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードが 409 (Conflict です)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクに、タスクの開始時点から計測されます、特定のコンピューティング ノードで実行できる最大経過時間を設定します。 制限時間内にタスクが完了しない場合、Batch service によって終了します。 既定値は、15 分です。 15 分より長いタイムアウトを指定することはできません。 場合は、バッチ サービス拒否が次のエラーです。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコマンドラインを実行する前に、バッチ サービスをコンピューティング ノードにダウンロードするファイルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この要素の下にリストされたファイルは、タスクの作業ディレクトリにあります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードでジョブのリリース タスクの作業ディレクトリを保持する時間の最小値を設定します。 この時刻より後は、作業ディレクトリとその内容はすべて、バッチ サービスは削除できます。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値が有限、コンピューティング ノードが削除または再イメージ化されるまでに、作業ディレクトリを保持するなどです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクを実行するユーザー id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、そのタスクは、タスクに一意の非管理者のユーザーとして実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobReleaseTask.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>