<Type Name="FailoverTestScenarioParameters" FullName="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters">
  <TypeSignature Language="C#" Value="public class FailoverTestScenarioParameters : System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FailoverTestScenarioParameters extends System.Fabric.Testability.Scenario.TestScenarioParameters" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverTestScenarioParameters&#xA;Inherits TestScenarioParameters" />
  <TypeSignature Language="F#" Value="type FailoverTestScenarioParameters = class&#xA;    inherit TestScenarioParameters" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenarioParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="128c6-101">このクラスは、FailoverTestScenario を構成するすべてのテスト パラメーターを定義します。</span><span class="sxs-lookup"><span data-stu-id="128c6-101">This class defines all the test parameters to configure the FailoverTestScenario.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTestScenarioParameters (System.Fabric.PartitionSelector partitionSelector, TimeSpan timeToRun, TimeSpan maxServiceStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan timeToRun, valuetype System.TimeSpan maxServiceStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.#ctor(System.Fabric.PartitionSelector,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.FailoverTestScenarioParameters : System.Fabric.PartitionSelector * TimeSpan * TimeSpan -&gt; System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" Usage="new System.Fabric.Testability.Scenario.FailoverTestScenarioParameters (partitionSelector, timeToRun, maxServiceStabilizationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="maxServiceStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="128c6-102">PartitionSelector がテストの対象となるパーティションを得られます。</span><span class="sxs-lookup"><span data-stu-id="128c6-102">PartitionSelector which gives the partition being targeted for the test.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="128c6-103">テストのフェールオーバーを実行する時間の合計。</span><span class="sxs-lookup"><span data-stu-id="128c6-103">The total time for which the failover test will run.</span></span></param>
        <param name="maxServiceStabilizationTimeout"><span data-ttu-id="128c6-104">テストが失敗する前に、エラーの後に安定してサービスを待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="128c6-104">The maximum amount of time to wait for the service to stabilize after a fault before failing the test.</span></span></param>
        <summary>
            <span data-ttu-id="128c6-105">FailoverTestScenarioParameters のコンス トラクター。</span><span class="sxs-lookup"><span data-stu-id="128c6-105">Constructor for the FailoverTestScenarioParameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxServiceStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxServiceStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxServiceStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.MaxServiceStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxServiceStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxServiceStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.MaxServiceStabilizationTimeout" />
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
            <span data-ttu-id="128c6-106">テストが失敗する前に、エラーの後に安定してサービスを待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="128c6-106">The maximum amount of time to wait for the service to stabilize after a fault before failing the test.</span></span>
            </summary>
        <value>
            <span data-ttu-id="128c6-107">フェールオーバーのシナリオを行使する開始日まで FailoverTestScenario はこの量が安定し、healthy にするのには、サービスの時間で待機多くてします。</span><span class="sxs-lookup"><span data-stu-id="128c6-107">Before start exercising failover scenarios, FailoverTestScenario waits at most this amount of time for the service to stabilize and to become healthy.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSelector">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionSelector PartitionSelector { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.PartitionSelector PartitionSelector" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.PartitionSelector" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionSelector As PartitionSelector" />
      <MemberSignature Language="F#" Value="member this.PartitionSelector : System.Fabric.PartitionSelector with get, set" Usage="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters.PartitionSelector" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="128c6-108">テストの対象にする必要があるパーティション」に進んで PartitionSelector です。</span><span class="sxs-lookup"><span data-stu-id="128c6-108">The PartitionSelector which gives the partition that needs to be targeted for the test.</span></span>
            </summary>
        <value>
            <span data-ttu-id="128c6-109"><see cref="T:System.Fabric.PartitionSelector" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="128c6-109">Returns <see cref="T:System.Fabric.PartitionSelector" /></span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>