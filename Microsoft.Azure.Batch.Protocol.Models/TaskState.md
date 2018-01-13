<Type Name="TaskState" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskState">
  <TypeSignature Language="C#" Value="public enum TaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskState" />
  <TypeSignature Language="F#" Value="type TaskState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            TaskState の値を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクは、キューに置かれたできの実行は、コンピューティング ノードに現在割り当てられていません。 タスクをこの状態に無効になっている後に有効になっているときに、作成時または失敗した実行後に再試行を待機しているときにします。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            タスクが実行するには通常、タスクが正常に完了したか、タスクが正常に完了し、再試行の制限が不足ため対象ではなくなりました。 タスクは、完了した場合は、タスクの起動時にエラーが発生した場合や、タスクが終了された場合にもマークされます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Preparing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="preparing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクは、コンピューティング ノードに割り当てられているが、ノード、完了に必要なジョブの準備タスクが待機しています。 ジョブの準備タスクが成功した場合、タスクが実行中に移動します。 ジョブの準備タスクが失敗した場合、タスクはアクティブに戻り、別のノードに割り当てられるに対象となります。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState Running = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            タスクが、コンピューティング ノードで実行します。 これには、リソース ファイルをダウンロードしたり、タスクで指定されたアプリケーション パッケージの配置などのタスク レベルの準備が含まれます - ことが必ずしもタスクのコマンドラインの実行が開始されたことです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>