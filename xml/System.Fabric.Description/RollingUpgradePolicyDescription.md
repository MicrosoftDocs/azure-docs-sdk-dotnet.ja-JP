<Type Name="RollingUpgradePolicyDescription" FullName="System.Fabric.Description.RollingUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public class RollingUpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradePolicyDescription extends System.Fabric.Description.UpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradePolicyDescription&#xA;Inherits UpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type RollingUpgradePolicyDescription = class&#xA;    inherit UpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="44ed1-101">ローリング アップグレード ポリシーの説明です。</span><span class="sxs-lookup"><span data-stu-id="44ed1-101">Description of the rolling upgrade policy.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="44ed1-102"><see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRestart">
      <MemberSignature Language="C#" Value="public bool ForceRestart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceRestart" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRestart As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceRestart : bool with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />
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
          <para><span data-ttu-id="44ed1-103">アップグレードの一部としてコード パッケージの変更がない場合でも、サービス ホストを再起動する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-103">Specifies if the service host should be restarted even when there are no code package changes as part of the upgrade.</span></span> <span data-ttu-id="44ed1-104">True の場合にこのフラグを設定、サービス構成ファイルまたはデータのパッケージの変更を動的に受け入れることができません。</span><span class="sxs-lookup"><span data-stu-id="44ed1-104">Set this flag to true if the service cannot dynamically accept config or data package changes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44ed1-105"><see cref="T:System.Boolean" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-105">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : System.Fabric.RollingUpgradeMode with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44ed1-106">型:<see cref="T:System.Fabric.RollingUpgradeMode" />アップグレードの種類を指定します (<see cref="T:System.Fabric.RollingUpgradeMode" />) アプリケーション インスタンスのアップグレードに使用します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-106">Type: <see cref="T:System.Fabric.RollingUpgradeMode" />Specifies the types of upgrade (<see cref="T:System.Fabric.RollingUpgradeMode" />) to be used for upgrading the application instance.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="44ed1-107"><see cref="T:System.Fabric.RollingUpgradeMode" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-107">Returns <see cref="T:System.Fabric.RollingUpgradeMode" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeReplicaSetCheckTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeReplicaSetCheckTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeReplicaSetCheckTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeReplicaSetCheckTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />
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
          <para><span data-ttu-id="44ed1-108">Service Fabric がサービスにクォーラムがない場合は、アップグレード ドメイン内のアプリケーション インスタンスのサービスをアップグレードする前に待機する期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="44ed1-108">Specifies the duration Service Fabric should wait before upgrading the services of an application instance in an upgrade domain if the services do not have quorum.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44ed1-109">期間 Service Fabric は、サービスがクォーラムを持っていない場合は、アップグレード ドメイン内のアプリケーション インスタンスのサービスをアップグレードする前に待機する必要があります。</span><span class="sxs-lookup"><span data-stu-id="44ed1-109">The duration Service Fabric should wait before upgrading the services of an application instance in an upgrade domain if the services do not have quorum.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>