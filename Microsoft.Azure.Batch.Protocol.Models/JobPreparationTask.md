<Type Name="JobPreparationTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask">
  <TypeSignature Language="C#" Value="public class JobPreparationTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTask" />
  <TypeSignature Language="F#" Value="type JobPreparationTask = class" />
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
            コンピューティング ノードのすべてのタスク上、特定のジョブの前に実行するジョブの準備タスク。
            </summary>
    <remarks>
            ジョブのタスクを実行するコンピューティング ノードを準備するジョブの準備を行うこともできます。 一般的に実行されるジョブの準備の活動が含まれます。 ジョブ内のすべてのタスクで使用される共通のリソース ファイルをダウンロードします。 ジョブの準備タスクは、コンピューティング ノード上の共有場所にこれらの一般的なリソース ファイルをダウンロードできます。 (AZ_BATCH_NODE_ROOT_DIR\shared)、またはそのジョブのすべてのタスクと通信できるように、コンピューティング ノード上でローカル サービスを開始します。 ジョブの準備タスク (つまり、その再試行回数は終了コード 0 で終了する前に枯渇) が失敗した場合のバッチのコンピューティング ノードで、このジョブのタスクは実行されません。 ノードは、イメージが再作成されるまで、このジョブのタスクを実行する対象外です。 ノードは、アクティブなままし、その他のジョブに使用できます。 ジョブの準備タスクは、同じコンピューティング ノード上で複数回を実行できます。 そのため、再実行を処理するジョブの準備タスクを記述する必要があります。 コンピューティング ノードが再起動された場合、ジョブの準備タスクがもう一度ノードで実行 rerunOnNodeRebootAfterSuccess が true の場合、またはジョブの準備タスクが既に完了しなかった場合、ジョブの他のタスクをスケジュールする前にします。 コンピューティング ノードが再イメージ化されるジョブの準備タスクは、ジョブのいずれかのタスクをスケジュールする前にもう一度実行されます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor" />
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
            JobPreparationTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; waitForSuccess = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; rerunOnNodeRebootAfterSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; rerunOnNodeRebootAfterSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, constraints, waitForSuccess, userIdentity, rerunOnNodeRebootAfterSuccess)" />
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
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="rerunOnNodeRebootAfterSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine">ジョブの準備タスクのコマンドラインです。</param>
        <param name="id">ジョブ内のジョブの準備タスクを一意に識別する文字列。</param>
        <param name="containerSettings">ジョブの準備タスクを実行するコンテナーの設定。</param>
        <param name="resourceFiles">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</param>
        <param name="environmentSettings">ジョブの準備タスクに対する環境変数設定の一覧。</param>
        <param name="constraints">ジョブの準備タスクに適用される制約します。</param>
        <param name="waitForSuccess">かどうか、バッチ サービスは、コンピューティング ノード上のジョブの他のタスクをスケジュールする前に正常に完了するジョブの準備タスクを待機する必要があります。 終了コード 0 で終了した場合、ジョブの準備タスクが正常に完了します。</param>
        <param name="userIdentity">ジョブの準備タスクを実行するユーザー id。</param>
        <param name="rerunOnNodeRebootAfterSuccess">かどうか、バッチ サービス再実行してください、ジョブの準備タスク コンピューティング ノードの後に再起動します。</param>
        <summary>
            JobPreparationTask クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
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
            取得またはジョブの準備タスクのコマンドラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。 このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの準備タスクに適用される制約を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
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
            取得またはジョブの準備タスクを実行するコンテナーの設定を設定します。
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
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
            取得またはジョブの準備タスクに対する環境変数設定の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
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
            取得または、ジョブ内のジョブの準備タスクを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ID は、ハイフンとアンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。 このプロパティを指定しない場合、Batch service は、'jobpreparation' の既定値を割り当てます。 ジョブ内の他のタスクがジョブの準備タスクと同じ ID を持つことはできません。 同じ id を持つタスクを送信しようとすると、バッチ サービスはエラー コード TaskIdSameAsJobPreparationTask; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードが 409 (Conflict です)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RerunOnNodeRebootAfterSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RerunOnNodeRebootAfterSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property RerunOnNodeRebootAfterSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RerunOnNodeRebootAfterSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rerunOnNodeRebootAfterSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Batch service コンピューティング ノードの再起動後に、ジョブの準備タスクを再実行するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            コンピューティング ノードが再イメージ化される場合、またはジョブの準備タスクが完了しなかった場合、ジョブの準備タスクが常に再実行 (例: タスクの実行中に再起動が発生したため)。 したがって、べき等になると、正常に動作する複数回実行した場合は、ジョブの準備タスクを作成する必要があります。 既定値は true です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
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
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
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
            取得またはジョブの準備タスクを実行するユーザー id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、タスクとして実行一意の非管理者のユーザーにタスク Windows ノードでは、または、Linux ノード上のプールに一意の非管理者のユーザーです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationTask.Validate " />
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
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスがコンピューティング ノード上のジョブの他のタスクをスケジュールする前に正常に完了するジョブの準備タスクを待機するかどうかを設定します。 終了コード 0 で終了した場合、ジョブの準備タスクが正常に完了します。
            </summary>
        <value>To be added.</value>
        <remarks>
            True で、ジョブの準備タスクは、コンピューティング ノードで失敗した場合、バッチ サービスは (制約要素で指定) と同じ場合は、その最大再試行回数までジョブの準備タスクを再試行します。 タスクがまだ完了していない場合が正常にすべての再試行後に、バッチ サービスはコンピューティング ノードにジョブのタスクのスケジュールを設定できませんし、します。 コンピューティング ノードは、アクティブおよびその他のジョブのタスクを実行する対象となるは残ります。 False の場合、バッチ サービスは、ジョブの準備タスクの完了を待機しません。 この例では、ジョブの他のタスクがジョブの準備タスクがまだ実行されているコンピューティング ノードで実行されているを開始することができます。コンティニュ ジョブの準備タスクが失敗した場合でも新しいタスクは、ノードにあるスケジュールします。 既定値は true です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>