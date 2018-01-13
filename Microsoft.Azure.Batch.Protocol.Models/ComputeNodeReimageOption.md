<Type Name="ComputeNodeReimageOption" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeReimageOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeReimageOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeReimageOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeReimageOption = " />
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
            ComputeNodeReimageOption の値を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="requeue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクの実行中のプロセスを終了し、タスクをキューに再登録します。 ノードがあると、タスクが再び実行します。 タスクが終了したらすぐには、ノードを再イメージ化します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="retaineddata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了し、すべてのタスク データ保持期間有効期限が切れるまで待機できるようにします。 待機中に新しいタスクをスケジュールしません。 すべてのタスクの保有期間の期限が切れている場合は、ノードを再イメージ化します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="taskcompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了できるようにします。 待機中に新しいタスクをスケジュールしません。 すべてのタスクが完了したときに、ノードを再イメージ化します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了します。 終了しましたが再実行されないことを示す failureInfo には、タスクが完了します。 タスクが終了したらすぐには、ノードを再イメージ化します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>