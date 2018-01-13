<Type Name="ChaosTestScenario" FullName="System.Fabric.Testability.Scenario.ChaosTestScenario">
  <TypeSignature Language="C#" Value="public sealed class ChaosTestScenario : System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ChaosTestScenario extends System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.ChaosTestScenario" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ChaosTestScenario&#xA;Inherits TestScenario" />
  <TypeSignature Language="F#" Value="type ChaosTestScenario = class&#xA;    inherit TestScenario" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Testability.Scenario.TestScenario</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class is deprecated. To manage Chaos, please use StartChaosAsync, StopChaosAsync, and GetChaosReportAsync APIs from FabricClient.TestManager instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ChaosTestScenario は、保持を強制しないでフェールオーバーとフォールト クラスターへ、TimetoRun 期限切れまでの間を長時間実行されるシナリオです。
            </summary>
    <remarks>
            テストが引き起こされる 'maxConcurrentFaults' まですべてのイテレーションとそのは検証、正常性と、クラスター内のすべてのサービスの可用性フォールトの次の反復処理する前にします。 任意の時点では、サービスを利用できる、または 'maxClusterStabilizationTimeout' で正常な場合、FabricValidationException とテストは失敗します。 イテレーションごとにシステムに起因する同時実行エラーは、障害一緒には発生しませんすべてのサービスを使用できなくなるか、データが失われるようにの安全を確保します。 これは、外部のデータ損失の可用性が発生することができます (chaos テスト エラーと同時実行)、発生する場合、予期しないエラー起因フォールトを負いません。 これは、テストに対して実行する非常に良好テストまたはシステムで発生したエラーどのような種類の可用性の損失やその他のサービスの予期しない問題の発生しないことを確認するワークロードをテストするステージングのクラスターが実行されています。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosTestScenario (System.Fabric.FabricClient fabricClient, System.Fabric.Testability.Scenario.ChaosTestScenarioParameters chaosScenarioParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClient fabricClient, class System.Fabric.Testability.Scenario.ChaosTestScenarioParameters chaosScenarioParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.#ctor(System.Fabric.FabricClient,System.Fabric.Testability.Scenario.ChaosTestScenarioParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.ChaosTestScenario : System.Fabric.FabricClient * System.Fabric.Testability.Scenario.ChaosTestScenarioParameters -&gt; System.Fabric.Testability.Scenario.ChaosTestScenario" Usage="new System.Fabric.Testability.Scenario.ChaosTestScenario (fabricClient, chaosScenarioParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricClient" Type="System.Fabric.FabricClient" />
        <Parameter Name="chaosScenarioParameters" Type="System.Fabric.Testability.Scenario.ChaosTestScenarioParameters" />
      </Parameters>
      <Docs>
        <param name="fabricClient">クラスターに接続し、エラーを引き起こしますに使用される FabricClient オブジェクトです。</param>
        <param name="chaosScenarioParameters">混乱の構成を定義する ChaosTestScenarioParameters をテストします。</param>
        <summary>
            ChaosTestScenario のコンス トラクター。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected override void OnDispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.OnDispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnDispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnDispose : bool -&gt; unit" Usage="chaosTestScenario.OnDispose disposing" />
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
        <param name="disposing">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</param>
        <summary>
            この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnExecuteAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.OnExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.OnExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="chaosTestScenario.OnExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.ChaosTestScenario/&lt;OnExecuteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</param>
        <summary>
            この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateScenarioAtExitAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task ValidateScenarioAtExitAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task ValidateScenarioAtExitAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.ChaosTestScenario.ValidateScenarioAtExitAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ValidateScenarioAtExitAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="override this.ValidateScenarioAtExitAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="chaosTestScenario.ValidateScenarioAtExitAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.ChaosTestScenario/&lt;ValidateScenarioAtExitAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token">この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。</param>
        <summary>
            この API は、Service Fabric プラットフォームのサポートをコードから呼び出されるものではありません。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>