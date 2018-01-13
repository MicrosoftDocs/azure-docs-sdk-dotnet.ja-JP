<Type Name="HealthEvent" FullName="System.Fabric.Health.HealthEvent">
  <TypeSignature Language="C#" Value="public sealed class HealthEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthEvent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthEvent" />
  <TypeSignature Language="F#" Value="type HealthEvent = class" />
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
      <para>ヘルス マネージャーによって追加された追加のメタデータを持つクラスター、アプリケーション ノードなどの正常性エンティティで報告される正常性の情報を表します。</para>
    </summary>
    <remarks>正常性イベントがなどの正常性クエリによって返される<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />です。
            含まれている<see cref="T:System.Fabric.Health.HealthInformation" />で正常性マネージャーに送信される、<see cref="T:System.Fabric.Health.HealthReport" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>正常性ストアに送信された正常性情報の取得、<see cref="T:System.Fabric.Health.HealthReport" />です。</para>
        </summary>
        <value>
          <para>正常性ストアに送信された正常性情報を<see cref="T:System.Fabric.Health.HealthReport" />です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public bool IsExpired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpired : bool" Usage="System.Fabric.Health.HealthEvent.IsExpired" />
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
          <para>正常性イベントの有効期限が切れているかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、正常性イベントの有効期限が切れました。<languageKeyword>false</languageKeyword>正常性イベントが、時に期限が切れていない場合、正常性ストアがクエリを評価します。</para>
        </value>
        <remarks>
          <para>イベントを期限切れにできるのは、RemoveWhenExpired が false の場合のみです。
            それ以外の場合、イベントはクエリによって返されずに、ストアから削除されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastErrorTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastErrorTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastErrorTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastErrorTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastErrorTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Error" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Error" />です。 定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</para>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Error" />、別の状態に遷移する前にします。 場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Error" />System.DateTime.FromFileTimeUtc(0) になります。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Error" />です。</para>
        </value>
        <remarks>
          <para>遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。
            スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。 などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>日付と時刻の正常性ストアによって、正常性レポートの最終変更日時を取得します。</para>
        </summary>
        <value>
          <para>日付と時刻の正常性ストアによって、正常性レポートの最終変更日時。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOkTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastOkTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastOkTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOkTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastOkTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Ok" />です。 定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</para>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Ok" />、別の状態に遷移する前にします。 場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Ok" />System.DateTime.FromFileTimeUtc(0) になります。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</para>
        </value>
        <remarks>
          <para>遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。
            スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。 などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastWarningTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastWarningTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastWarningTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastWarningTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastWarningTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Warning" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Warning" />です。 定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</para>
          <para>場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />または<see cref="F:System.Fabric.Health.HealthState.Error" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Warning" />、別の状態に遷移する前にします。 場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Warning" />System.DateTime.FromFileTimeUtc(0) になります。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
        </value>
        <remarks>
          <para>遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。
            スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。 などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SourceUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SourceUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SourceUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>正常性レポートをソースから送信されたときの日時を取得します。</para>
        </summary>
        <value>
          <para>日付と、正常性レポートがソースによって送信された時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvent.ToString " />
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
            正常性イベントの文字列表現を取得します。
            </summary>
        <returns>正常性イベントの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>