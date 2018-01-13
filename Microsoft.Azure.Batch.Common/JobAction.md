<Type Name="JobAction" FullName="Microsoft.Azure.Batch.Common.JobAction">
  <TypeSignature Language="C#" Value="public enum JobAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobAction" />
  <TypeSignature Language="F#" Value="type JobAction = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            タスクが完了したときに、タスクを含むジョブで実行する操作。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="Disable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobAction Disable = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobAction.Disable" />
      <MemberSignature Language="VB.NET" Value="Disable" />
      <MemberSignature Language="F#" Value="Disable = 1" Usage="Microsoft.Azure.Batch.Common.JobAction.Disable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            ジョブを無効にします。 
            </summary>
        <remarks>これは、呼び出すことと同じ<see cref="M:Microsoft.Azure.Batch.JobOperations.DisableJob(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />disableTasks 値を持つ<see cref="F:Microsoft.Azure.Batch.Common.DisableJobOption.Requeue" />します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobAction None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobAction.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.Batch.Common.JobAction.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            必要はありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobAction Terminate = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobAction.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 2" Usage="Microsoft.Azure.Batch.Common.JobAction.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ジョブを終了します。
            </summary>
        <remarks>終了の理由で<see cref="P:Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />"TaskFailed"に設定されています。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>