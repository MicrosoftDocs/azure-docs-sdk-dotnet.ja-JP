<Type Name="FabricUpgradeUpdateDescription" FullName="System.Fabric.Description.FabricUpgradeUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeUpdateDescription : System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeUpdateDescription extends System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeUpdateDescription&#xA;Inherits UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type FabricUpgradeUpdateDescription = class&#xA;    inherit UpgradeUpdateDescriptionBase" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradeUpdateDescriptionBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターのアップグレードの動作を記述するアップグレード パラメーターを変更するために使用します。
            以下を参照してください。<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" /></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricUpgradeUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.FabricUpgradeUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" /> クラスのインスタンスを作成します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
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
            各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />そのアプリケーションのアプリケーションのヘルスを評価するために使用します。
            </para>
          <para>
            アプリケーションが、マップで指定されていない場合、アプリケーション マニフェストで検出された表す ApplicationHealthPolicy が評価のため使用されます。 </para>
          <para>
            アップグレード中に、クラスターの正常性を評価するカスタム アプリケーションの正常性ポリシーにも使用<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。
            </para>
          <para>
            マップは、既定では、以前にアプリケーションの正常性ポリシーを設定する、更新プログラムを適用しないことが null です。
            アプリケーションの正常性ポリシーを更新するには、マップを作成し、必要なアプリケーションのエントリを追加します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
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
          <para><see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" /> を取得または設定します。</para>
        </summary>
        <value>
          <para>クラスターの正常性ポリシーはアップグレード中にクラスターの正常性を評価するために使用します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
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
          <para><see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" /> を取得または設定します。</para>
        </summary>
        <value>
          <para>クラスターのアップグレードのヘルス ポリシーはアップグレード中にクラスターの正常性を評価するために使用します。</para>
        </value>
        <remarks>
          <para>
            アップグレードのヘルス ポリシーを使用するときに<see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />に設定されている<languageKeyword>true</languageKeyword>です。 デルタの評価は既定では無効です。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>