<Type Name="SubtaskState" FullName="Microsoft.Azure.Batch.Common.SubtaskState">
  <TypeSignature Language="C#" Value="public enum SubtaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SubtaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.SubtaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum SubtaskState" />
  <TypeSignature Language="F#" Value="type SubtaskState = " />
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
            サブタスクの状態。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.SubtaskState Completed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.SubtaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 2" Usage="Microsoft.Azure.Batch.Common.SubtaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            サブタスクが実行するには通常、it が正常に完了またはサブタスクが正常に完了し、再試行の制限が不足ため対象ではなくなりました。  サブタスクは、完了した場合は、サブタスクの起動エラーが発生しました、またはサブタスクが終了したときにもマークされます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.SubtaskState Preparing = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.SubtaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 0" Usage="Microsoft.Azure.Batch.Common.SubtaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            サブタスクは、コンピューティング ノードに割り当てられているが、ノード、完了に必要なジョブの準備タスクが待機しています。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.SubtaskState Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.SubtaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="Microsoft.Azure.Batch.Common.SubtaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.SubtaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            サブタスクは、コンピューティング ノード上で実行しています。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>