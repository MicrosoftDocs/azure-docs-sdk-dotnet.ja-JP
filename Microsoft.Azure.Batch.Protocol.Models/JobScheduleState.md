<Type Name="JobScheduleState" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState">
  <TypeSignature Language="C#" Value="public enum JobScheduleState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobScheduleState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobScheduleState" />
  <TypeSignature Language="F#" Value="type JobScheduleState = " />
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
            JobScheduleState の値を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Active" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            ジョブのスケジュールがアクティブであり、スケジュールに従ってジョブが作成されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState Completed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Completed" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            終了時刻に到達するか、明示的に終了しているユーザーをスケジュールが終了しました。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState Deleting = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 4" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="deleting")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            ユーザーが、スケジュールが削除されることを要求されましたが、削除操作が進行中です。 スケジューラは、このスケジュールの新しいジョブは開始されませんし、任意の既存のジョブとタスクは、アクティブなジョブを含め、スケジュールが削除されます。 スケジュールは、すべてのジョブとタスクは、スケジュールが削除されたときに削除されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="disabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ユーザーは、スケジュールを無効にします。 スケジューラは、このスケジュールで、新しいジョブは開始されませんが、既存のアクティブなジョブを実行し続けます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState Terminating = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminating")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            スケジュールが他の作業を行うには明示的に設定されているか、ユーザーによる中断しますが、終了操作が進行中です。 スケジューラがこのスケジュールの新しいジョブを開始しませんも、既存のジョブのアクティブです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>