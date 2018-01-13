<Type Name="ComputeNodeDeallocationOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeDeallocationOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeDeallocationOption = " />
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
            プールのサイズが減少している場合は、処理する方法、既に実行中のタスクし、プールからそれらを実行してノードをいつ削除することがありますを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了し、そのキューに再登録します。 このタスクは、ジョブが有効になると再び実行されます。 タスクが終了するとすぐにノードを削除します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了し、すべてのタスク データ保持期間有効期限が切れるまで待機できるようにします。 待機中に新しいタスクをスケジュールしません。 すべてのタスク保有期間が終了したとき、ノードを削除します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了できるようにします。 待機中に新しいタスクをスケジュールしません。 すべてのタスクが完了するとノードを削除します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了します。 タスクは再び実行されることがありません。 タスクが終了するとすぐにノードを削除します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>