<Type Name="UpgradeUpdateDescriptionBase" FullName="System.Fabric.Description.UpgradeUpdateDescriptionBase">
  <TypeSignature Language="C#" Value="public abstract class UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit UpgradeUpdateDescriptionBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type UpgradeUpdateDescriptionBase = class" />
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
      <para>抽象基本クラスを表す<see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" />と<see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />です。
            アプリケーションまたはクラスターのアップグレードの動作を記述するアップグレード パラメーターを変更するのには、このクラスを使用できます。 参照してください<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />と<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />使用状況を表示します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected UpgradeUpdateDescriptionBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UpgradeUpdateDescriptionBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.UpgradeUpdateDescriptionBase" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureAction&gt; FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureAction&gt; FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As Nullable(Of UpgradeFailureAction)" />
      <MemberSignature Language="F#" Value="member this.FailureAction : Nullable&lt;System.Fabric.UpgradeFailureAction&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="T:System.Fabric.UpgradeFailureAction" />です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.UpgradeFailureAction" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRestart">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForceRestart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForceRestart" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRestart As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForceRestart : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.ForceRestart" />
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
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckStableDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeDomainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />です。 </para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.RollingUpgradeMode&gt; UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.RollingUpgradeMode&gt; UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As Nullable(Of RollingUpgradeMode)" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : Nullable&lt;System.Fabric.RollingUpgradeMode&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.RollingUpgradeMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="T:System.Fabric.RollingUpgradeMode" />です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.RollingUpgradeMode" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeReplicaSetCheckTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeReplicaSetCheckTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeReplicaSetCheckTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeReplicaSetCheckTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeReplicaSetCheckTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>新しい値の設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />です。</para>
        </summary>
        <value>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" /> の新しい値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>