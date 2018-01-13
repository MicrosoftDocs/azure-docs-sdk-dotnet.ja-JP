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
      <para><span data-ttu-id="7f8e1-101">クラスターのアップグレードには、特定のクラスターの正常性を評価する正常性ポリシーを定義します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-101">Defines a health policy used to evaluate the health of the cluster specific to cluster upgrade.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="7f8e1-102">と共に使用する、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />をクラスターの正常性を評価し、監視対象のクラスターのアップグレードが成功したかロールバックする必要があるかを判断します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-102">It’s used together with <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> to evaluate cluster health and determine whether the monitored cluster upgrade is successful or needs to be rolled back.</span></span></para>
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
          <para><span data-ttu-id="7f8e1-103"><see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" /> class.</span></span></para>
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
          <para><span data-ttu-id="7f8e1-104">取得またはクラスターのアップグレード中に許可されているノードの正常性低下の許可される最大の割合を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-104">Gets or sets the maximum allowed percentage of nodes health degradation allowed during cluster upgrades.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="7f8e1-105">最大デルタの正常性低下の割合です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-105">The maximum allowed percentage of delta health degradation.</span></span> <span data-ttu-id="7f8e1-106">有効な値は、0 から 100 までの整数値です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-106">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="7f8e1-107">差分は、アップグレードの開始時のノードの状態と、正常性評価の時のノードの状態の間で測定されます。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-107">The delta is measured between the state of the nodes at the beginning of upgrade and the state of the nodes at the time of the health evaluation.</span></span> <span data-ttu-id="7f8e1-108">チェックは、すべてのアップグレード ドメインのアップグレード完了後に実行され、クラスターのグローバル状態が許容範囲内であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-108">The check is performed after every upgrade domain upgrade completion to make sure the global state of the cluster is within tolerated limits.</span></span> <span data-ttu-id="7f8e1-109">既定値は、10% です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-109">The default value is 10%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="7f8e1-110">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-110">The specified value was outside the range of integer values from zero to 100.</span></span></para>
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
          <para><span data-ttu-id="7f8e1-111">取得または許容されるクラスターのアップグレード中に許可されているアップグレード ドメイン ノードの正常性低下の割合の最大値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-111">Gets or sets the maximum allowed percentage of upgrade domain nodes health degradation allowed during cluster upgrades.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7f8e1-112">アップグレード ドメインのデルタの正常性低下の割合が最大です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-112">The maximum allowed percentage of upgrade domain delta health degradation.</span></span> <span data-ttu-id="7f8e1-113">有効な値は、0 から 100 までの整数値です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-113">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="7f8e1-114">差分は、アップグレードの開始時のアップグレード ドメイン ノードの状態と、正常性評価の時のアップグレード ドメイン ノードの状態の間で測定されます。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-114">The delta is measured between the state of the upgrade domain nodes at the beginning of upgrade and the state of the upgrade domain nodes at the time of the health evaluation.</span></span> <span data-ttu-id="7f8e1-115">チェックは、すべてのアップグレード ドメインのアップグレード完了後にすべての完了したアップグレード ドメインに対して実行され、アップグレード ドメインの状態が許容範囲内であることを確認します。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-115">The check is performed after every upgrade domain upgrade completion for all completed upgrade domains to make sure the state of the upgrade domains is within tolerated limits.</span></span> <span data-ttu-id="7f8e1-116">既定値は、15% です。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-116">The default value is 15%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="7f8e1-117">指定した値は、0 から 100 までの整数値の範囲外でした。</span><span class="sxs-lookup"><span data-stu-id="7f8e1-117">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>