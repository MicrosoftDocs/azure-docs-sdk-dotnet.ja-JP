<Type Name="ChaosTestScenarioParameters" FullName="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters">
  <TypeSignature Language="C#" Value="public class ChaosTestScenarioParameters : System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ChaosTestScenarioParameters extends System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ChaosTestScenarioParameters&#xA;Inherits TestScenarioParameters" />
  <TypeSignature Language="F#" Value="type ChaosTestScenarioParameters = class&#xA;    inherit TestScenarioParameters" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenarioParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class is deprecated. Please use System.Fabric.Chaos.DataStructures.ChaosParameters instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            このクラスは、ChaosTestScenario を構成するすべてのテスト パラメーターを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosTestScenarioParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.ChaosTestScenarioParameters : TimeSpan * int64 * bool * TimeSpan -&gt; System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" Usage="new System.Fabric.Testability.Scenario.ChaosTestScenarioParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout">テストが失敗する前に、フォールトのイテレーションの後に安定してクラスター全体の待機する時間の最大量。</param>
        <param name="maxConcurrentFaults">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。 高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。 この 2 または 3 を使用することをお勧めします。</param>
        <param name="enableMoveReplicaFaults">有効またはエラー MovePrimary と MoveSecondary を無効にします。</param>
        <param name="timeToRun"></param>
        <summary>
          <para><see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <returns>ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxClusterStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxClusterStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxClusterStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.MaxClusterStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxClusterStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxClusterStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.MaxClusterStabilizationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テストが失敗する前に、エラーの後に安定してクラスターを待機する時間の最大量。
            </summary>
        <value>
            繰り返すたびに、ChaosTestScenario 待ちます多くてこの時間に異常な状態になるクラスターの数
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenIterations">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenIterations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenIterations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.WaitTimeBetweenIterations" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenIterations As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenIterations : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters.WaitTimeBetweenIterations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この値によってバインドされるランダムな期間の 2 つのイテレーションまでの時間を待機します。
            </summary>
        <value>
            ChaosTestScenario の 2 つの連続したイテレーション間の時間の分離
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>