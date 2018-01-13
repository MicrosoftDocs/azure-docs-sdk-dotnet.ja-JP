<Type Name="ClusterUpgradeHealthPolicy" FullName="System.Fabric.Health.ClusterUpgradeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpgradeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterUpgradeHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターのアップグレードには、特定のクラスターの正常性を評価する正常性ポリシーを定義します。</para>
    </summary>
    <remarks>
      <para>と共に使用する、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />をクラスターの正常性を評価し、監視対象のクラスターのアップグレードが成功したかロールバックする必要があるかを判断します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterUpgradeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはクラスターのアップグレード中に許可されているノードの正常性低下の許可される最大の割合を設定します。
            </para>
        </summary>
        <value>
          <para>最大デルタの正常性低下の割合です。 有効な値は、0 から 100 までの整数値です。</para>
        </value>
        <remarks>差分は、アップグレードの開始時のノードの状態と、正常性評価の時のノードの状態の間で測定されます。 チェックは、すべてのアップグレード ドメインのアップグレード完了後に実行され、クラスターのグローバル状態が許容範囲内であることを確認します。 既定値は、10% です。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または許容されるクラスターのアップグレード中に許可されているアップグレード ドメイン ノードの正常性低下の割合の最大値を設定します。</para>
        </summary>
        <value>
          <para>アップグレード ドメインのデルタの正常性低下の割合が最大です。 有効な値は、0 から 100 までの整数値です。</para>
        </value>
        <remarks>差分は、アップグレードの開始時のアップグレード ドメイン ノードの状態と、正常性評価の時のアップグレード ドメイン ノードの状態の間で測定されます。 チェックは、すべてのアップグレード ドメインのアップグレード完了後にすべての完了したアップグレード ドメインに対して実行され、アップグレード ドメインの状態が許容範囲内であることを確認します。 既定値は、15% です。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>