<Type Name="ConfigurationUpgradeDescription" FullName="System.Fabric.Description.ConfigurationUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ConfigurationUpgradeDescription = class" />
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
      <para>Service Fabric クラスター構成のアップグレードについて記述するパラメーターをカプセル化するクラスを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigurationUpgradeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationUpgradeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ConfigurationUpgradeDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterConfiguration">
      <MemberSignature Language="C#" Value="public string ClusterConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterConfiguration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.ClusterConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterConfiguration As String" />
      <MemberSignature Language="F#" Value="member this.ClusterConfiguration : string" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.ClusterConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これは、適用されるクラスター構成をクラスターにします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckRetryTimeout" />
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
          <para>取得またはアプリケーションまたはクラスターが正常でない場合は、正常性チェックを実行を試みるまでの時間の長さを設定します。</para>
        </summary>
        <value>
          <para>状態の実行を試みるまでの時間の長さは、アプリケーションまたはクラスターが正常ではないかどうかを確認します。</para>
        </value>
        <remarks>
          <para>正常性チェックの再試行を防ぐためには、設定、<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />プロパティの値を<see cref="F:System.TimeSpan.Zero" />です。 既定では、 <see cref="F:System.TimeSpan.Zero" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckStableDuration" />
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
          <para>取得または時間の長さを設定するアプリケーションまたはクラスター必要があります healthy のままです正常性チェックに合格したし、次のアップグレード ドメインへのアップグレードを続行する前にします。</para>
        </summary>
        <value>
          <para>時間の長さ、アプリケーションまたはクラスターに正常な保つようにします。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckWaitDuration" />
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
          <para>取得または正常性チェック プロセスを開始する前に、アップグレード ドメインの完了後に待機する時間の長さを設定します。</para>
        </summary>
        <value>
          <para>正常性を開始する前に、アップグレード ドメインの完了後に待機する時間の長さは、プロセスを確認します。</para>
        </value>
        <remarks>
          <para>使用するには、待ち時間が無限、正常性チェックの設定、<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />プロパティの値を<see cref="F:System.TimeSpan.Zero" />です。 既定では、 <see cref="F:System.TimeSpan.Zero" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentDeltaUnhealthyNodes" />
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
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyApplications" />
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
          <para>許容される異常なアプリケーションからの割合の最大値を取得、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />です。</para>
        </summary>
        <value>
          <para>許容される異常なアプリケーションの割合の最大値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyNodes" />
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
          <para>取得または異常なノードの最大許容パーセンテージを設定します。</para>
        </summary>
        <value>
          <para>許容される異常なノードの割合の最大値。 有効な値は、0 から 100 までの整数値です。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、異常な可能性のあるノードの最大許容パーセンテージを表します。この値を超えるとクラスターはエラーの状態と見なされます。 許容パーセンテージ内であっても、1 つ以上の異常なノードがある場合は、正常性は Warning として評価されます。
            これは、クラスター内のノードの総数に対して異常なノードの数で割ることによって計算されます。
            切り上げ計算が実行され、少数のノードに対する 1 つのエラーは許容されます。 既定のパーセンテージは 0 です。
            </para>
          <para>大規模なクラスターでは、ダウンしているか修復を必要とするノードがいくつか必ず存在するため、それが許容されるようにこのパーセンテージを構成する必要があります。</para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
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
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationUpgradeDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="configurationUpgradeDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ConfigurationUpgradeDescription の文字列表現を取得します。
            </summary>
        <returns>ConfigurationUpgradeDescription の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeDomainTimeout" />
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
          <para>取得またはドメインのアップグレードのタイムアウトを設定します。</para>
        </summary>
        <value>
          <para>ドメインのアップグレードのタイムアウト。</para>
        </value>
        <remarks>
          <para>既定値は TimeSpan.FromSeconds (uint です。MaxValue)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeTimeout" />
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
          <para>取得またはアップグレードのタイムアウトを設定します。</para>
        </summary>
        <value>
          <para>アップグレードのタイムアウト。</para>
        </value>
        <remarks>
          <para>既定値は TimeSpan.FromSeconds (uint です。MaxValue)。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>