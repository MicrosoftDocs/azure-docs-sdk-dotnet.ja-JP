<Type Name="DisableJobOption" FullName="Microsoft.Azure.Batch.Common.DisableJobOption">
  <TypeSignature Language="C#" Value="public enum DisableJobOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableJobOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.DisableJobOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum DisableJobOption" />
  <TypeSignature Language="F#" Value="type DisableJobOption = " />
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
            無効にするジョブ操作中にアクティブなタスクの処理方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了し、そのキューに再登録します。 このタスクは、ジョブが有効になると再び実行されます。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            タスクの実行を終了します。 タスクは再び実行されることがありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Wait">
      <MemberSignature Language="C#" Value="Wait" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableJobOption Wait = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableJobOption.Wait" />
      <MemberSignature Language="VB.NET" Value="Wait" />
      <MemberSignature Language="F#" Value="Wait = 2" Usage="Microsoft.Azure.Batch.Common.DisableJobOption.Wait" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableJobOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            実行中のタスクを完了できるようにします。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>