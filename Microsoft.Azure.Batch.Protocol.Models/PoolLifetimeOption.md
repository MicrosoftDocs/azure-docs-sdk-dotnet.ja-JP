<Type Name="PoolLifetimeOption" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption">
  <TypeSignature Language="C#" Value="public enum PoolLifetimeOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PoolLifetimeOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum PoolLifetimeOption" />
  <TypeSignature Language="F#" Value="type PoolLifetimeOption = " />
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
            PoolLifetimeOption の値を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="Job" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption Job = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.Job" />
      <MemberSignature Language="VB.NET" Value="Job" />
      <MemberSignature Language="F#" Value="Job = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.Job" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="job")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            プールは、専用であるジョブの有効期間にわたって存在します。 バッチ サービスは、ジョブを作成するときに、プールを作成します。 'ジョブ' オプションをジョブのスケジュールに適用すると、バッチ サービスは、すべてのジョブのスケジュールで作成された新しい自動プールを作成します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="JobSchedule">
      <MemberSignature Language="C#" Value="JobSchedule" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption JobSchedule = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.JobSchedule" />
      <MemberSignature Language="VB.NET" Value="JobSchedule" />
      <MemberSignature Language="F#" Value="JobSchedule = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption.JobSchedule" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="jobschedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            プールは、ジョブ スケジュールの有効期間にわたって存在します。 バッチ サービスは、スケジュールでの最初のジョブを作成するときに、プールを作成します。 ジョブではなく、ジョブのスケジュールにのみ、このオプションを適用することがあります。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>