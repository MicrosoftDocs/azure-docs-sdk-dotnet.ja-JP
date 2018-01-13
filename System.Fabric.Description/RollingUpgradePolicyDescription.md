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
      <para>ローリング アップグレード ポリシーの説明です。</para>
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
          <para><see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" /> クラスの新しいインスタンスを初期化します。</para>
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
          <para>アップグレードの一部としてコード パッケージの変更がない場合でも、サービス ホストを再起動する必要があるかどうかを指定します。 True の場合にこのフラグを設定、サービス構成ファイルまたはデータのパッケージの変更を動的に受け入れることができません。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
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
          <para>型:<see cref="T:System.Fabric.RollingUpgradeMode" />アップグレードの種類を指定します (<see cref="T:System.Fabric.RollingUpgradeMode" />) アプリケーション インスタンスのアップグレードに使用します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.RollingUpgradeMode" /> を返します。</para>
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
          <para>Service Fabric がサービスにクォーラムがない場合は、アップグレード ドメイン内のアプリケーション インスタンスのサービスをアップグレードする前に待機する期間を指定します。</para>
        </summary>
        <value>
          <para>期間 Service Fabric は、サービスがクォーラムを持っていない場合は、アップグレード ドメイン内のアプリケーション インスタンスのサービスをアップグレードする前に待機する必要があります。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>