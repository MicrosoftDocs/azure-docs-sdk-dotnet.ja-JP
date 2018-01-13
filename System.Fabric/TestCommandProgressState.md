<Type Name="TestCommandProgressState" FullName="System.Fabric.TestCommandProgressState">
  <TypeSignature Language="C#" Value="public enum TestCommandProgressState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TestCommandProgressState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TestCommandProgressState" />
  <TypeSignature Language="VB.NET" Value="Public Enum TestCommandProgressState" />
  <TypeSignature Language="F#" Value="type TestCommandProgressState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            この列挙型では、テスト コマンドの状態を示します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancelled">
      <MemberSignature Language="C#" Value="Cancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Cancelled = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Cancelled" />
      <MemberSignature Language="VB.NET" Value="Cancelled" />
      <MemberSignature Language="F#" Value="Cancelled = 5" Usage="System.Fabric.TestCommandProgressState.Cancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            テスト コマンドは CancelTestCommandAsync() を使用して、ユーザーによって取り消されました
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="System.Fabric.TestCommandProgressState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            テスト コマンドが正常に完了し、現在実行されていません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Faulted">
      <MemberSignature Language="C#" Value="Faulted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Faulted = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Faulted" />
      <MemberSignature Language="VB.NET" Value="Faulted" />
      <MemberSignature Language="F#" Value="Faulted = 4" Usage="System.Fabric.TestCommandProgressState.Faulted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            テスト コマンドが失敗し、現在実行されていません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ForceCancelled">
      <MemberSignature Language="C#" Value="ForceCancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState ForceCancelled = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.ForceCancelled" />
      <MemberSignature Language="VB.NET" Value="ForceCancelled" />
      <MemberSignature Language="F#" Value="ForceCancelled = 6" Usage="System.Fabric.TestCommandProgressState.ForceCancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            テスト コマンドは、force パラメーターを true に設定と CancelTestCommandAsync() を使用するユーザーによって取り消されました
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.TestCommandProgressState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            テスト コマンドの状態が正しくありません。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBack">
      <MemberSignature Language="C#" Value="RollingBack" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState RollingBack = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.RollingBack" />
      <MemberSignature Language="VB.NET" Value="RollingBack" />
      <MemberSignature Language="F#" Value="RollingBack = 2" Usage="System.Fabric.TestCommandProgressState.RollingBack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            テスト コマンドはロールバック内部システム状態致命的なエラーが発生しましたかは、ユーザーによって取り消されました。  「ロールバックしています」は、ユーザー状態を参照していません。  たとえば、CancelTestCommandAsync() を TestCommandType.PartitionDataLoss の種類のコマンドを呼び出すと、「ロールバックしています」の状態は限りません (コマンドをデータの損失を十分に離れた進めたと仮定) サービスのデータが復元されます。  
            システムはバックアップ/クリーニング内部システム状態をロールアップするコマンドに関連付けられていることを示します。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="System.Fabric.TestCommandProgressState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            テスト コマンドが実行中です。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>