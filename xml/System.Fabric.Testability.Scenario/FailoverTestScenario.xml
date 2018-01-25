<Type Name="FailoverTestScenario" FullName="System.Fabric.Testability.Scenario.FailoverTestScenario">
  <TypeSignature Language="C#" Value="public sealed class FailoverTestScenario : System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FailoverTestScenario extends System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.FailoverTestScenario" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FailoverTestScenario&#xA;Inherits TestScenario" />
  <TypeSignature Language="F#" Value="type FailoverTestScenario = class&#xA;    inherit TestScenario" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenario</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8fe66-101">FailoverTestScenario は、エラーの系列を FailoverTestScenarioParameters で PartitionSelector によって定義された特定のパーティションに対して実行されるテストです。</span><span class="sxs-lookup"><span data-stu-id="8fe66-101">The FailoverTestScenario is a test which runs a series of faults against a specific partition defined by the PartitionSelector in the FailoverTestScenarioParameters.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8fe66-102">いくつかの特定のフェールオーバー シナリオでパーティションを配置を誘発されるため、それらのパスがテストされ、実行、エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="8fe66-102">The faults induced put the partition through some specific failover scenarios to ensure those paths are tested and exercised.</span></span> <span data-ttu-id="8fe66-103">テストが実行されると同時に、サービスに対して、ワークロードを実行すると、発生させることと、サービスでのバグを検出する可能性が増加します。</span><span class="sxs-lookup"><span data-stu-id="8fe66-103">Running your workload against the service at the same time as the test being run will increase the chances of inducing and discovering bugs with the service.</span></span> <span data-ttu-id="8fe66-104">プライマリ、セカンダリのエラーが誘発されるおよびステートレス インスタンスは RestartReplica(only persisted)、RemoveReplica、ResartDeployedCodePackage、MovePrimary (だけステートフル)、MoveSecondary (ステートフルのみ)、RestartPartition (データ損失なし)。</span><span class="sxs-lookup"><span data-stu-id="8fe66-104">The faults induced for the Primary, Secondaries and stateless instances are RestartReplica(only persisted), RemoveReplica, ResartDeployedCodePackage, MovePrimary (only stateful), MoveSecondary (Only stateful), RestartPartition (no data loss).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverTestScenario (System.Fabric.FabricClient fabricClient, System.Fabric.Testability.Scenario.FailoverTestScenarioParameters testScenarioParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClient fabricClient, class System.Fabric.Testability.Scenario.FailoverTestScenarioParameters testScenarioParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.#ctor(System.Fabric.FabricClient,System.Fabric.Testability.Scenario.FailoverTestScenarioParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.FailoverTestScenario : System.Fabric.FabricClient * System.Fabric.Testability.Scenario.FailoverTestScenarioParameters -&gt; System.Fabric.Testability.Scenario.FailoverTestScenario" Usage="new System.Fabric.Testability.Scenario.FailoverTestScenario (fabricClient, testScenarioParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricClient" Type="System.Fabric.FabricClient" />
        <Parameter Name="testScenarioParameters" Type="System.Fabric.Testability.Scenario.FailoverTestScenarioParameters" />
      </Parameters>
      <Docs>
        <param name="fabricClient"><span data-ttu-id="8fe66-105">クラスターに接続し、エラーを引き起こしますに使用される FabricClient オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="8fe66-105">FabricClient object which will be used to connect to the cluster and induce the faults.</span></span></param>
        <param name="testScenarioParameters"><span data-ttu-id="8fe66-106">フェールオーバーの構成を定義する FailoverTestScenarioParameters をテストします。</span><span class="sxs-lookup"><span data-stu-id="8fe66-106">FailoverTestScenarioParameters which define the configuration for the failover test.</span></span></param>
        <summary>
            <span data-ttu-id="8fe66-107">FailoverTestScenario のコンス トラクター。</span><span class="sxs-lookup"><span data-stu-id="8fe66-107">Constructor for the FailoverTestScenario.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected override void OnDispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.OnDispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnDispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnDispose : bool -&gt; unit" Usage="failoverTestScenario.OnDispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="8fe66-108">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-108">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8fe66-109">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-109">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnExecuteAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.OnExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.OnExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="failoverTestScenario.OnExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.FailoverTestScenario/&lt;OnExecuteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="8fe66-110">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-110">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8fe66-111">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-111">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateScenarioAtExitAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task ValidateScenarioAtExitAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task ValidateScenarioAtExitAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.FailoverTestScenario.ValidateScenarioAtExitAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateScenarioAtExitAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.ValidateScenarioAtExitAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="failoverTestScenario.ValidateScenarioAtExitAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.FailoverTestScenario/&lt;ValidateScenarioAtExitAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="8fe66-112">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-112">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="8fe66-113">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="8fe66-113">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>