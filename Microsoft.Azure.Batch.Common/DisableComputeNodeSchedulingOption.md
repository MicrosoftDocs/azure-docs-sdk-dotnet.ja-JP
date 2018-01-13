<Type Name="DisableComputeNodeSchedulingOption" FullName="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption">
  <TypeSignature Language="C#" Value="public enum DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableComputeNodeSchedulingOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="F#" Value="type DisableComputeNodeSchedulingOption = " />
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
            実行中のタスクを行うにはどのような指定とコンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了し、そのキューに再登録します。 このタスクは、ジョブが有効になると再び実行されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了できるようにします。 待機中に新しいタスクをスケジュールしません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了します。 タスクは再び実行されることがありません。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>