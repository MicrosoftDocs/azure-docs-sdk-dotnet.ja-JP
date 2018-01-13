<Type Name="AllocationState" FullName="Microsoft.Azure.Batch.Common.AllocationState">
  <TypeSignature Language="C#" Value="public enum AllocationState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AllocationState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.AllocationState" />
  <TypeSignature Language="VB.NET" Value="Public Enum AllocationState" />
  <TypeSignature Language="F#" Value="type AllocationState = " />
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
            プールのサイズを変更するかどうかを示します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Resizing">
      <MemberSignature Language="C#" Value="Resizing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Resizing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />
      <MemberSignature Language="VB.NET" Value="Resizing" />
      <MemberSignature Language="F#" Value="Resizing = 1" Usage="Microsoft.Azure.Batch.Common.AllocationState.Resizing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            プールのサイズを変更します。つまり、コンピューティング ノードの中に追加またはプールから削除します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Steady">
      <MemberSignature Language="C#" Value="Steady" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Steady = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />
      <MemberSignature Language="VB.NET" Value="Steady" />
      <MemberSignature Language="F#" Value="Steady = 0" Usage="Microsoft.Azure.Batch.Common.AllocationState.Steady" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            プールのサイズを変更できません。 進行中のプール内のノードの数を変更することはありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopping">
      <MemberSignature Language="C#" Value="Stopping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Stopping = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />
      <MemberSignature Language="VB.NET" Value="Stopping" />
      <MemberSignature Language="F#" Value="Stopping = 2" Usage="Microsoft.Azure.Batch.Common.AllocationState.Stopping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            プールがサイズ変更が、ユーザーは、サイズ変更を停止することを要求したが、停止要求がまだ完了していません。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>