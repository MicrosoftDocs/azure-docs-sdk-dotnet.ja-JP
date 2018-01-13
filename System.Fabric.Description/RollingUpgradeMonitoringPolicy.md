<Type Name="RollingUpgradeMonitoringPolicy" FullName="System.Fabric.Description.RollingUpgradeMonitoringPolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeMonitoringPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMonitoringPolicy = class" />
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
      <para>ポリシーの監視のローリング アップグレードをカプセル化するクラスを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeMonitoringPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradeMonitoringPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>
          <para>初期化のプロパティを設定する、<see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />次の既定値を持つクラス。</para>
          <para>プロパティ</para>
          <para>既定値</para>
          <list type="table">
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />
                </para>
                <para>この値を変更する必要がありますまたは<see cref="T:System.ArgumentException" />アップグレードを開始する前にスローされます。</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.TimeSpan.Zero" />
                </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="T:System.TimeSpan" />既定値は 120 秒の値。
                    </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
                </para>
              </term>
              <description>
                <para>600 秒</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
                </para>
              </term>
              <description>
                <para>TimeSpan.FromSeconds (uint です。MaxValue)</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
                </para>
              </term>
              <description>
                <para>TimeSpan.FromSeconds (uint です。MaxValue)</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeFailureAction FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.UpgradeFailureAction FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As UpgradeFailureAction" />
      <MemberSignature Language="F#" Value="member this.FailureAction : System.Fabric.UpgradeFailureAction with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはアップグレードに失敗した場合に実行するアクションを設定します。 既定では、 <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />です。</para>
        </summary>
        <value>
          <para>アップグレードに失敗した場合に実行するアクション。</para>
        </value>
        <remarks>
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />プロパティの既定値から変更する必要があります<see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />または<see cref="T:System.ArgumentException" />アップグレードを開始する前にスローされます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> プロパティが <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> に設定されている。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
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
          <para>で指定されたアクションの正常性チェックで障害が継続的に、アップグレードが失敗した時間の長さを設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</para>
        </summary>
        <value>
          <para>正常性チェックを時間の長さは、継続的に失敗することができます。</para>
        </value>
        <remarks>
          <para>既定値は 600 秒です。 設定<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />に<see cref="F:System.TimeSpan.Zero" />1 つの正常性チェックのみになります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
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
          <para>取得または正常性は、次のアップグレード ドメインへのアップグレードを続行する前に継続的に渡す必要がありますをチェックする時間の長さを設定します。</para>
        </summary>
        <value>
          <para>正常性チェックを時間の長さは、継続的に渡す必要があります。</para>
        </value>
        <remarks>
          <para>既定値は 120 秒です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
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
          <para>取得または正常性チェックを実行する前に、アップグレード ドメインの完了後に待機する時間の長さを設定します。</para>
        </summary>
        <value>
          <para>正常性チェックを実行する前に、アップグレード ドメインの完了後に待機する時間の長さ。</para>
        </value>
        <remarks>
          <para>既定では、 <see cref="F:System.TimeSpan.Zero" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
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
          <para>どのアップグレード ドメインの処理が、アップグレードは失敗しによって指定された操作の前に実行できる時間の長さを取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</para>
        </summary>
        <value>
          <para>どのアップグレード ドメインのタイムアウト。</para>
        </value>
        <remarks>
          <para>既定値は TimeSpan.FromSeconds (uint です。MaxValue)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
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
          <para>取得または設定した場合、アップグレードの失敗およびによって指定された操作の前に、全体的なアップグレードが実行できる時間の長さ<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</para>
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