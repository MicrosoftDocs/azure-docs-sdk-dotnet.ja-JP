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
            <span data-ttu-id="f8f3e-101">このクラスは、ChaosTestScenario を構成するすべてのテスト パラメーターを定義します。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-101">This class defines all the test parameters to configure the ChaosTestScenario.</span></span>
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
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="f8f3e-102">テストが失敗する前に、フォールトのイテレーションの後に安定してクラスター全体の待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-102">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration before failing the test.</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="f8f3e-103">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-103">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="f8f3e-104">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-104">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="f8f3e-105">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-105">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="f8f3e-106">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-106">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"></param>
        <summary>
          <para><span data-ttu-id="f8f3e-107"><see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-107">Initializes a new instance of the <see cref="T:System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="f8f3e-108">ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="f8f3e-108">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
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
            <span data-ttu-id="f8f3e-109">テストが失敗する前に、エラーの後に安定してクラスターを待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-109">The maximum amount of time to wait for the cluster to stabilize after a fault before failing the test.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f8f3e-110">繰り返すたびに、ChaosTestScenario 待ちます多くてこの時間に異常な状態になるクラスターの数</span><span class="sxs-lookup"><span data-stu-id="f8f3e-110">After each iteration, the ChaosTestScenario waits for at most this amount of time for the cluster to become healthy</span></span>
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
            <span data-ttu-id="f8f3e-111">この値によってバインドされるランダムな期間の 2 つのイテレーションまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="f8f3e-111">Wait time between two iterations for a random duration bound by this value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f8f3e-112">ChaosTestScenario の 2 つの連続したイテレーション間の時間の分離</span><span class="sxs-lookup"><span data-stu-id="f8f3e-112">The time-separation between two consecutive iterations of the ChaosTestScenario</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>