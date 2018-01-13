<Type Name="RepairTaskHealthCheckState" FullName="System.Fabric.Repair.RepairTaskHealthCheckState">
  <TypeSignature Language="C#" Value="public enum RepairTaskHealthCheckState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskHealthCheckState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskHealthCheckState" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskHealthCheckState" />
  <TypeSignature Language="F#" Value="type RepairTaskHealthCheckState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>修復タスクが準備または Restoring 状態になる修復タスクの正常性チェックのワークフローの状態を指定します。</para>
    </summary>
    <remarks>修復タスクは、準備と状態の復元が入ったときに、個別の正常性チェックが行われます。</remarks>
  </Docs>
  <Members>
    <Member MemberName="InProgress">
      <MemberSignature Language="C#" Value="InProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState InProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.InProgress" />
      <MemberSignature Language="VB.NET" Value="InProgress" />
      <MemberSignature Language="F#" Value="InProgress = 1" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.InProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            正常性チェックが進行中であることを示します
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotStarted">
      <MemberSignature Language="C#" Value="NotStarted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState NotStarted = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.NotStarted" />
      <MemberSignature Language="VB.NET" Value="NotStarted" />
      <MemberSignature Language="F#" Value="NotStarted = 0" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.NotStarted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            正常性チェックが開始されていないことを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Skipped">
      <MemberSignature Language="C#" Value="Skipped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState Skipped = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.Skipped" />
      <MemberSignature Language="VB.NET" Value="Skipped" />
      <MemberSignature Language="F#" Value="Skipped = 3" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.Skipped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            正常性チェックがスキップされたことを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="Succeeded" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState Succeeded = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Succeeded" />
      <MemberSignature Language="F#" Value="Succeeded = 2" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.Succeeded" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            正常性チェックが成功したことを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TimedOut">
      <MemberSignature Language="C#" Value="TimedOut" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState TimedOut = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.TimedOut" />
      <MemberSignature Language="VB.NET" Value="TimedOut" />
      <MemberSignature Language="F#" Value="TimedOut = 4" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.TimedOut" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            正常性チェックがタイムアウトしたことを示します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>