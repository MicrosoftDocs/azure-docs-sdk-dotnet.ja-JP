<Type Name="MonitoredRollingApplicationUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class MonitoredRollingApplicationUpgradePolicyDescription : System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MonitoredRollingApplicationUpgradePolicyDescription extends System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MonitoredRollingApplicationUpgradePolicyDescription&#xA;Inherits MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingApplicationUpgradePolicyDescription = class&#xA;    inherit MonitoredRollingUpgradePolicyDescription" />
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
      <para><span data-ttu-id="6967a-101">アプリケーションのアップグレードを実行するときに使用する動作について説明します。</span><span class="sxs-lookup"><span data-stu-id="6967a-101">Describes the behavior to use when performing an application upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoredRollingApplicationUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6967a-102"><see cref="T:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6967a-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6967a-103">取得またはアップグレード中のアプリケーションに対して実行する正常性がチェックするときに使用する正常性ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6967a-103">Gets or sets the health policy to use when performing health checks against an upgrading application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6967a-104">正常性を実行するときに使用する正常性ポリシーは、アップグレード中のアプリケーションに対してを確認します。</span><span class="sxs-lookup"><span data-stu-id="6967a-104">The health policy to use when performing health checks against an upgrading application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>