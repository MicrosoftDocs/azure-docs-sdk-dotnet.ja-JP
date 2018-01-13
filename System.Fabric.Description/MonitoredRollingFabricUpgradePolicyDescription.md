<Type Name="MonitoredRollingFabricUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class MonitoredRollingFabricUpgradePolicyDescription : System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MonitoredRollingFabricUpgradePolicyDescription extends System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MonitoredRollingFabricUpgradePolicyDescription&#xA;Inherits MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingFabricUpgradePolicyDescription = class&#xA;    inherit MonitoredRollingUpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.MonitoredRollingUpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターのアップグレードを実行するときに使用する動作について説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoredRollingFabricUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの正常性評価の一部としてアプリケーションのヘルスを評価するポリシーが使用されるアプリケーションの正常性を設定します。 
            </summary>
        <value>アプリケーションの正常性ポリシーは、指定したアプリケーションの正常性を評価するために使用します。</value>
        <remarks>
          <para>
            クラスターのアップグレード中に、クラスターの正常性を評価して、クラスターがまだ正常であるかどうかを決定します。 クラスターの正常性評価の一部として、すべてのアプリケーションが評価され、クラスターの正常性で集計します。
            アプリケーションの正常性ポリシー マップを使用して、クラスターの評価の一部としてアプリケーションを評価します。
            </para>
          <para>
            各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />そのアプリケーションのアプリケーションのヘルスを評価するために使用します。</para>
          <para>
            アプリケーションが、マップで指定されていない場合、アプリケーション マニフェストで検出された表す ApplicationHealthPolicy が評価のため使用されます。 </para>
          <para>
            アップグレード中に、クラスターの正常性を評価するカスタム アプリケーションの正常性ポリシーにも使用<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
          <para>
            マップは、既定では空です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public bool EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : bool with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはデルタ評価が有効になっているかどうかを示すフラグを設定します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>デルタの正常性評価を有効にするとします。<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </value>
        <remarks>
          <para>デルタの評価を有効にすると、クラスターの正常性評価の制限が許容されるは、正常性の面のパフォーマンスの低下がグローバルに、すべてのノードとごとに評価される各アップグレード ドメインの両方でことによって確認されます。 指定された許容しきい値<see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />です。</para>
          <para>デルタの評価は既定では無効にします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアップグレード中のクラスターに対してパフォーマンスの正常性がチェックするときに使用する正常性ポリシーを設定します。</para>
        </summary>
        <value>
          <para>正常性を実行するときに使用する正常性ポリシーは、アップグレード中のクラスターに対してを確認します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterUpgradeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアップグレード中のクラスターに対してパフォーマンスの正常性をチェックするときに使用するデルタの正常性ポリシーを設定します。</para>
        </summary>
        <value>
          <para>正常性を実行するときに使用するデルタの正常性ポリシーは、アップグレード中のクラスターに対してを確認します。</para>
        </value>
        <remarks>
          <para>
            アップグレードのヘルス ポリシーを使用するときに<see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />に設定されている<languageKeyword>true</languageKeyword>です。 デルタの評価は既定では無効にします。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>