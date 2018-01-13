<Type Name="ApplicationUpgradeProgress" FullName="System.Fabric.ApplicationUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ApplicationUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeProgress" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeProgress = class" />
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
      <para>
            アプリケーション インスタンスのアップグレード状態を表します。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アップグレード対象としてアプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para>アップグレード対象としてアプリケーションの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
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
          <para>アップグレード対象として、アプリケーションの型名を取得します。</para>
        </summary>
        <value>
          <para>アップグレード対象として、アプリケーションの型名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
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
          <para>予測の所要時間は、現在のアップグレード ドメインの処理に費やされたを取得します。</para>
        </summary>
        <value>
          <para>推定経過時間では、現在のアップグレード ドメインの処理に費やされました。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainProgress">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>現在のアップグレード ドメイン内のノードの詳細なアップグレードの進行状況を示します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.UpgradeDomainProgress" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureReason&gt; FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureReason&gt; FailureReason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            アップグレードが失敗した場合は、アップグレードの失敗のカテゴリを取得します。
            </para>
        </summary>
        <value>
          <para>アップグレードの失敗のカテゴリ。 <see cref="T:System.Fabric.UpgradeFailureReason" /></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FailureTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FailureTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            アップグレードが失敗した時刻を取得します。
            </para>
        </summary>
        <value>
          <para>時刻 (utc) のアップグレードが失敗しました。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChangedUpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains (System.Fabric.ApplicationUpgradeProgress previousProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains(class System.Fabric.ApplicationUpgradeProgress previousProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChangedUpgradeDomains (previousProgress As ApplicationUpgradeProgress) As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.GetChangedUpgradeDomains : System.Fabric.ApplicationUpgradeProgress -&gt; System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="applicationUpgradeProgress.GetChangedUpgradeDomains previousProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="previousProgress">
          <para>前の<see cref="T:System.Fabric.ApplicationUpgradeProgress" />オブジェクト。</para>
        </param>
        <summary>
          <para>変更されたアップグレード ドメインのコレクションを返すヘルパー メソッドを指定します、<see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" />状態または<see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" />以降状態、<see cref="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" />メソッドが呼び出されました。</para>
        </summary>
        <returns>
          <para>アップグレード ドメインのコレクションを返すヘルパー メソッド。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>アプリケーション名またはアプリケーションの種類の<paramref name="previousProgress" />パラメーターは、アプリケーションの名前またはこのオブジェクトのアプリケーションの種類と一致します。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
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
          <para>このアップグレードの進行状況の次のアップグレード ドメインを取得します。</para>
        </summary>
        <value>
          <para>このアップグレードの進行状況の次のアップグレード ドメイン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollingUpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode RollingUpgradeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode RollingUpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RollingUpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradeMode : System.Fabric.RollingUpgradeMode" Usage="System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
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
          <para>このアップグレードの進行状況のローリング アップグレードのモードを取得します。</para>
        </summary>
        <value>
          <para>このアップグレードの進行状況のローリング アップグレード モードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            アップグレードが開始された時刻を取得します。
            </para>
        </summary>
        <value>
          <para>Utc 形式でアップグレードが開始された時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string TargetApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string" Usage="System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
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
          <para>アップグレード中、アプリケーションの種類のバージョンを取得します。</para>
        </summary>
        <value>
          <para>アップグレード中、アプリケーションの種類のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationUpgradeProgress.ToString " />
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
            アプリケーション アップグレードの進行状況の文字列表現を取得します。
            </summary>
        <returns><see cref="T:System.Fabric.ApplicationUpgradeProgress" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>データとアプリケーションの正常性を評価する正常性マネージャーによって使用されるアルゴリズムを記述する評価を取得します。 </para>
        </summary>
        <value>
          <para>データとアプリケーションの正常性を評価する正常性マネージャーによって使用されるアルゴリズムを記述する評価します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDescription As ApplicationUpgradeDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : System.Fabric.Description.ApplicationUpgradeDescription" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationUpgradeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>現在のアップグレードの動作を記述するパラメーターを取得します。</para>
        </summary>
        <value>
          <para>現在のアップグレードの動作を記述するパラメーター。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            アップグレードに失敗した時点で、システムがどのようなアクションを実行しているがの構造化された情報を取得します。
            </para>
        </summary>
        <value>
          <para>アップグレード ドメインの進行状況の詳細 <see cref="T:System.Fabric.UpgradeDomainProgress" /></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このアプリケーションのアップグレードのアップグレード ドメインとアップグレードの状態のコレクションを取得します。</para>
        </summary>
        <value>
          <para>アップグレード ドメインと、このアプリケーションのアップグレードのアップグレードの状態のコレクション。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
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
          <para>取得される予測所要時間は、現在の全体的な処理に費やされたをアップグレードします。</para>
        </summary>
        <value>
          <para>推定経過時間では、現在の全体的なアップグレードの処理に費やされました。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.ApplicationUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ApplicationUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As ApplicationUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.ApplicationUpgradeState" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションのアップグレード プロセスの全体的な状態を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの全体的な状態では、プロセスをアップグレードします。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeStatusDetails">
      <MemberSignature Language="C#" Value="public string UpgradeStatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeStatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeStatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeStatusDetails : string" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
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
          <para>エラー メッセージを含むアップグレードの詳細なステータスを取得します。 </para>
        </summary>
        <value>
          <para>エラー メッセージを含むアップグレードの詳細なステータス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>