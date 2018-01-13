<Type Name="TaskState" FullName="Microsoft.Azure.Batch.Common.TaskState">
  <TypeSignature Language="C#" Value="public enum TaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.TaskState" />
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
  <Docs>
    <summary>
            タスクの状態。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.TaskState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクは、キューに置かれたできの実行は、コンピューティング ノードに現在割り当てられていません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="Microsoft.Azure.Batch.Common.TaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            タスクが実行するには通常、タスクが正常に完了したか、タスクが正常に完了し、再試行の制限が不足ため対象ではなくなりました。  タスクは、完了した場合は、タスクの起動時にエラーが発生した場合や、タスクが終了された場合にもマークされます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskState Preparing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskState.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 1" Usage="Microsoft.Azure.Batch.Common.TaskState.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクは、コンピューティング ノードに割り当てられているが、ノード、完了に必要なジョブの準備タスクが待機しています。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskState Running = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 2" Usage="Microsoft.Azure.Batch.Common.TaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            タスクが、コンピューティング ノードで実行します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>