<Type Name="HealthInformation" FullName="System.Fabric.Health.HealthInformation">
  <TypeSignature Language="C#" Value="public sealed class HealthInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthInformation" />
  <TypeSignature Language="F#" Value="type HealthInformation = class" />
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
      <para>一般的な正常性レポートの情報を表します。
            正常性クエリによって返されるすべての正常性イベントと、正常性ストアに送信されるすべての正常性レポートで含まれます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthInformation (string sourceId, string property, System.Fabric.Health.HealthState healthState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceId, string property, valuetype System.Fabric.Health.HealthState healthState) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.#ctor(System.String,System.String,System.Fabric.Health.HealthState)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthInformation : string * string * System.Fabric.Health.HealthState -&gt; System.Fabric.Health.HealthInformation" Usage="new System.Fabric.Health.HealthInformation (sourceId, property, healthState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="property" Type="System.String" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
      </Parameters>
      <Docs>
        <param name="sourceId">
          <para>レポートのソース。 できません<languageKeyword>null</languageKeyword>または空です。
            これは、「システム」、レポート作成システム コンポーネントの予約されたキーワードであるで開始できません。</para>
        </param>
        <param name="property">
          <para>レポートのプロパティです。 できません<languageKeyword>null</languageKeyword>または空です。</para>
        </param>
        <param name="healthState">
          <para>レポートの正常性状態。 指定する必要があります。
            いずれかを指定する必要があります、 <see cref="F:System.Fabric.Health.HealthState.Error" />、<see cref="F:System.Fabric.Health.HealthState.Warning" />または<see cref="F:System.Fabric.Health.HealthState.Ok" />値。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Health.HealthInformation" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <paramref name="property" />ことはできません<languageKeyword>null</languageKeyword>です。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>指定された<paramref name="healthState" />はサポートされていません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="AutoSequenceNumber">
      <MemberSignature Language="C#" Value="public const long AutoSequenceNumber = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 AutoSequenceNumber = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const AutoSequenceNumber As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable AutoSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            正常性のクライアントで有効なシーケンス番号に置き換え、自動シーケンス番号。
            </summary>
        <remarks>正常性のクライアントは、自動のシーケンス番号を持つレポートを受信すると、有効なシーケンス番号を自動シーケンス番号に置き換えます。
            同じプロセスで増加するシーケンス番号が保証されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Health.HealthInformation.Description" />
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
          <para>取得またはヘルス情報の説明を設定します。 監視対象の条件に関する情報を追加するために使用フリー テキストを表します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.String" />人間の判読できる形式で、ヘルス情報が記載されています。</para>
        </value>
        <remarks>
          <para>説明の文字列の最大文字数は 4096 文字です。
            指定された文字列が長い場合は、これは自動的に切り捨てられます。
            説明の最後の文字にマーカー「[ブラウズ]」が含まれて、切り捨てられた場合、文字列の合計サイズは 4096 文字です。
            マーカーの存在でユーザーにその切り捨てことを示しますが発生しました。
            切り捨てられた場合、説明が元の文字列からより小さい 4096 文字に注意してください。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthInformation.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レポートに使用される監視対象の条件の重大度を示す正常性の状態を取得します。</para>
        </summary>
        <value>
          <para>レポートに使用される監視対象の条件の重大度を示す正常性状態。</para>
        </value>
        <remarks>
          <para>
            許容されるヘルス状態は<see cref="F:System.Fabric.Health.HealthState.Ok" />、<see cref="F:System.Fabric.Health.HealthState.Warning" />と<see cref="F:System.Fabric.Health.HealthState.Error" />です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Property">
      <MemberSignature Language="C#" Value="public string Property { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Property" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Property" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Property As String" />
      <MemberSignature Language="F#" Value="member this.Property : string" Usage="System.Fabric.Health.HealthInformation.Property" />
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
          <para>正常性レポートのプロパティを取得します。</para>
        </summary>
        <value>
          <para>正常性レポートのプロパティです。 と共に、 <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />、正常性に関する情報を一意に識別します。</para>
        </value>
        <remarks>
          <para>
            プロパティは、<see cref="T:System.String" />とレポーター柔軟にレポートをトリガーする状態条件を分類できるようにする固定列挙ではありません。
            レポート機能など、 <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "AvailableDisk"プロパティをそのノードに報告できるように、"A"は、ノードで使用可能なディスクの状態を監視できます。
            レポート機能<see cref="P:System.Fabric.Health.HealthInformation.SourceId" />"B"は同じノードでプロパティ「接続」を報告できるようにノードの接続を監視できます。
            Health store にこれらのレポートは、指定したノードに対して個別の正常性イベントとして扱われます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveWhenExpired">
      <MemberSignature Language="C#" Value="public bool RemoveWhenExpired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveWhenExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveWhenExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveWhenExpired : bool with get, set" Usage="System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
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
          <para>取得または有効期限が切れるときに、レポートが health store から削除されたかどうかを示す値を設定します。 場合設定<languageKeyword>false</languageKeyword>レポートが経過したときにエラーとして扱われます。 <languageKeyword>false</languageKeyword>既定です。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は、レポートは、それ以外の有効期限が切れたときに、正常性ストアから削除するか<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>
          <para>クライアントを定期的にレポートをする必要があります設定が<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> <languageKeyword>false</languageKeyword> (既定値)。
            この方法は、レポート機能に問題があります。 デッドロック) および正常性レポートの有効期限し、エンティティとしてこのフラグが設定されるときに、エンティティがエラーで評価された、レポートできない<see cref="F:System.Fabric.Health.HealthState.Error" />です。
            定期的なヘルスのクライアントは、正常性のクライアントがバッチ処理による遅延のために有効期限より高い頻度でレポートを送信する必要があります、ワイヤと正常性トランスポート遅延をメッセージが処理を格納します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または正常性については、使用して、正常性ストアで陳腐化検出に関連付けられているシーケンス番号を設定します。
            <see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" /> よりも大きい必要があります。</para>
        </summary>
        <value>
          <para>正常性に関する情報に関連付けられているレポートのシーケンス番号。</para>
        </value>
        <remarks>
          <para>正常性ストアは、レポートのシーケンス番号を使用して、古いレポートを検出できます。
            </para>
          <para>多くの場合のレポート機能は、シーケンス番号を指定する必要はありません。 既定値<see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />代わりに使用されることができます。 正常性のクライアントは、自動のシーケンス番号を持つレポートを受信すると、同じプロセスで増加することが保証される有効なシーケンス番号を生成します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="System.Fabric.Health.HealthInformation.SourceId" />
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
          <para>正常性に関する情報を生成したウォッチドッグ/システム コンポーネントを識別するソース名を取得します。</para>
        </summary>
        <value>
          <para>レポートを作成するウォッチドッグ/システム コンポーネントを識別して、正常性レポートのソース。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="System.Fabric.Health.HealthInformation.TimeToLive" />
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
          <para>取得または正常性レポートが有効ではどのくらいの期間を設定します。 TimeSpan.Zero より大きくなければなりません。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.TimeSpan" />正常性レポートの有効期限の時刻を表すです。</para>
        </value>
        <remarks>
          <para>クライアントは定期的に報告、ときに有効期限よりも頻度が高くなるとレポートを送信する必要があります。
            クライアントは、遷移の報告場合、time to live を無限に設定できます。</para>
          <para>場合、ヘルス情報を含む正常性イベントが health store から削除するか、有効期限が経過すると、<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />は<languageKeyword>true</languageKeyword>場合に発生したエラー、評価または<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />は<languageKeyword>false</languageKeyword>です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>指定した値が無効でした。 0 より大きい、継続時間を指定してください。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthInformation.ToString " />
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
            正常性に関する情報について説明する文字列を作成します。
            </summary>
        <returns>正常性についての説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>
            不明なシーケンス番号には、正常性ストアによっては許容されませんいる無効なシーケンス番号です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>