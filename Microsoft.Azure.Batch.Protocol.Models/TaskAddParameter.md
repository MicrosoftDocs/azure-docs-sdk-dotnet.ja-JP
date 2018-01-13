<Type Name="TaskAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter">
  <TypeSignature Language="C#" Value="public class TaskAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddParameter" />
  <TypeSignature Language="F#" Value="type TaskAddParameter = class" />
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
            追加する Azure のバッチ タスクです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor" />
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
            TaskAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,Microsoft.Azure.Batch.Protocol.Models.ExitConditions,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.AffinityInformation,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.UserIdentity,Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings,Microsoft.Azure.Batch.Protocol.Models.TaskDependencies,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * Microsoft.Azure.Batch.Protocol.Models.ExitConditions * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.AffinityInformation * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings * Microsoft.Azure.Batch.Protocol.Models.TaskDependencies * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter (id, commandLine, displayName, containerSettings, exitConditions, resourceFiles, outputFiles, environmentSettings, affinityInfo, constraints, userIdentity, multiInstanceSettings, dependsOn, applicationPackageReferences, authenticationTokenSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="exitConditions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="affinityInfo" Type="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="multiInstanceSettings" Type="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
        <Parameter Name="dependsOn" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
      </Parameters>
      <Docs>
        <param name="id">ジョブ内のタスクを一意に識別する文字列。</param>
        <param name="commandLine">タスクのコマンドラインです。</param>
        <param name="displayName">タスクの表示名。</param>
        <param name="containerSettings">タスクを実行するコンテナーの設定。</param>
        <param name="exitConditions">バッチ サービスの応答方法、タスクが完了したときにします。</param>
        <param name="resourceFiles">バッチ サービスはコマンドラインを実行する前にコンピューティング ノードにダウンロードされるファイルの一覧。</param>
        <param name="outputFiles">バッチ サービスはコマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧です。</param>
        <param name="environmentSettings">タスクの環境変数設定の一覧。</param>
        <param name="affinityInfo">新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒント。</param>
        <param name="constraints">このタスクに適用される実行の制約。</param>
        <param name="userIdentity">タスクを実行するユーザー id。</param>
        <param name="multiInstanceSettings">タスクが複数のインスタンス、タスクは、複数インスタンスのタスクを実行する方法に関する情報を格納であることを示すオブジェクトです。</param>
        <param name="dependsOn">このタスクは、このタスクに依存します。</param>
        <param name="applicationPackageReferences">バッチ サービスは、コマンドラインを実行する前に、コンピューティング ノードに配置するアプリケーション パッケージの一覧。</param>
        <param name="authenticationTokenSettings">バッチを実行するタスクを使用する認証トークンの設定は、操作を処理します。</param>
        <summary>
            TaskAddParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityInfo As AffinityInformation" />
      <MemberSignature Language="F#" Value="member this.AffinityInfo : Microsoft.Azure.Batch.Protocol.Models.AffinityInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AffinityInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または新しいタスクを開始するコンピューティング ノードを選択する、Batch service によって使用できる局所性のヒントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコマンドラインを実行する前に、コンピューティング ノードに、バッチ サービスを展開するアプリケーション パッケージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            アプリケーション パッケージがダウンロードされ、作業ディレクトリのタスクではない、共有ディレクトリに配置します。 そのため、参照されているパッケージは既にコンピューティング ノードでありは最新の状態場合、し、これは再ダウンロードされません;コンピューティング ノードで、既存のコピーが使用されます。 参照先のアプリケーション パッケージをインストールできない場合、例については、パッケージが削除されたか、ダウンロードが失敗したため、タスクが失敗したためです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationTokenSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービス操作を実行するタスクが使用できる認証トークンの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティが設定されている場合、バッチ サービスは、アカウント アクセス キーを必要とせず、Batch service 操作を認証するために使用する認証トークンを使用してタスクを提供します。 トークンが AZ_BATCH_AUTHENTICATION_TOKEN 環境変数を介して提供されます。 トークンを使用して、タスクが実行できる操作は、設定によって決まります。 たとえば、タスクは、ジョブを他のタスクを追加するか、またはその他のタスクは、ジョブのジョブの状態を確認するために、ジョブのアクセス許可を要求できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
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
            取得またはタスクのコマンドラインを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            マルチ インスタンスのタスクの主要なタスクとサブタスクをすべての調整のコマンドラインの実行が完了した後、コマンドラインは、主要なタスクとして実行されます。 コマンド ライン シェルが動作しないためできません利用して環境変数の展開などのシェルの機能の。 このような機能を利用する場合を呼び出すように、コマンド ライン シェルたとえば"cmd/c MyCommand"を使用して windows または"/bin/sh-c MyCommand"Linux でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
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
            取得または、このタスクに適用される実行制約を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            制約を指定しない場合、maxTaskRetryCount ジョブでは、指定された maxTaskRetryCount は、maxWallClockTime と retentionTime は有限です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
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
            取得またはタスクを実行するコンテナーの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このタスクを実行している、プールに containerConfiguration 設定がある場合は、これはも設定する必要があります。 このタスクを実行している、プールには、設定 containerConfiguration が割り当てられていない、これを設定しないでください。 これを指定すると、AZ_BATCH_NODE_ROOT_DIR (ノードの Azure Batch のディレクトリのルート) の下のすべてのディレクトリに再帰的には、コンテナーにマップされて、すべてのタスクの環境変数が、コンテナーにマップおよびタスクのコマンドラインは、コンテナーで実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As TaskDependencies" />
      <MemberSignature Language="F#" Value="member this.DependsOn : Microsoft.Azure.Batch.Protocol.Models.TaskDependencies with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependsOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDependencies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このタスクが依存しているタスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            依存しているすべてのタスクが正常に完了するまで、このタスクはスケジュールされません。 失敗の再試行カウントを使い果たすそれらのタスクのいずれかの場合は、このタスクがスケジュールされることはありません。 ジョブがない場合は、usesTaskDependencies true で、この要素に設定が存在、要求がエラー コード TaskDependenciesNotSpecifiedOnJob です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
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
            取得またはタスクの環境変数設定の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitConditions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitConditions As ExitConditions" />
      <MemberSignature Language="F#" Value="member this.ExitConditions : Microsoft.Azure.Batch.Protocol.Models.ExitConditions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitConditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitConditions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、タスクが完了したときに、バッチ サービスがどのように対処する必要がありますか。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
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
            取得または、ジョブ内のタスクを一意に識別する文字列を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。 ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるのみ、ジョブ内の 2 つの Id はない必要があります)。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiInstanceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiInstanceSettings As MultiInstanceSettings" />
      <MemberSignature Language="F#" Value="member this.MultiInstanceSettings : Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="multiInstanceSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定があること示しタスク複数インスタンスのタスクでは、複数インスタンスのタスクを実行する方法に関する情報を格納するオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、Batch service は、コマンドラインの実行後にコンピューティング ノードからアップロードするファイルの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            複数インスタンスのタスク、主要なタスクを実行するコンピューティング ノードから、ファイルのみアップロードされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
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
            マルチ インスタンスのタスクを主なタスクを実行するコンピューティング ノードにリソース ファイルのみダウンロードされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
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
            取得またはタスクを実行するユーザー id を設定します。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddParameter.Validate " />
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