<Type Name="CorrelationFilter" FullName="Microsoft.Azure.ServiceBus.CorrelationFilter">
  <TypeSignature Language="C#" Value="public sealed class CorrelationFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorrelationFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorrelationFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type CorrelationFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            相関関係のフィルター式を表します。
            </summary>
    <remarks>
      <para>
            CorrelationFilter では、一連の条件は到着したメッセージのユーザー アカウントとシステム プロパティのいずれかと一致するが保持されます。
            一般的な用途は、一致する、<see cref="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" />プロパティがアプリケーションにもと照合することができます<see cref="P:Microsoft.Azure.ServiceBus.Message.ContentType" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.Label" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.MessageId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />、 <see cref="P:Microsoft.Azure.ServiceBus.Message.To" />、いずれかユーザー定義のプロパティ。
            受信メッセージのプロパティ値が相関関係フィルターに指定された値と等しいときに、一致するものが存在すると判断されます。 文字列式の比較では大文字と小文字を区別します。 複数の一致するプロパティを指定する場合、フィルターは論理 AND 条件として、つまり、すべての条件が一致するフィルターの一致する必要がありますそれらを結合します。
            </para>
      <para>
            CorrelationFilter は、相関関係の等値のみを処理するフィルターの宣言の効率的なショートカットを提供します。
            ここでは、式の lexigraphical 分析のコストを回避できます。
            だけでなくが相関関係のフィルターは、宣言時に最適化されますが、実行時にも最適化されます。
            関連付けフィルターの一致は、o (1) に定義されている相関関係のフィルターのセットの複雑さを集計、ハッシュ テーブルの検索を削減できます。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" /> クラスの新しいインスタンスを既定値で初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorrelationFilter (string correlationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string correlationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (correlationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.CorrelationFilter : string -&gt; Microsoft.Azure.ServiceBus.CorrelationFilter" Usage="new Microsoft.Azure.ServiceBus.CorrelationFilter correlationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="correlationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="correlationId">相関関係の識別子です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.CorrelationFilter" />指定された関連付け識別子を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされる、<paramref name="correlationId" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージのコンテンツの種類。
            </summary>
        <value>メッセージのコンテンツ タイプ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関連付けの識別子
            </summary>
        <value>相関関係の識別子。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アプリケーション固有のラベル。
            </summary>
        <value>アプリケーション固有のラベル。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの識別子。
            </summary>
        <value>メッセージの識別子。</value>
        <remarks>MessageId の最大サイズとは、128 文字です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージのアプリケーション固有のプロパティです。
            </summary>
        <value>メッセージのアプリケーションの特定プロパティです。</value>
        <remarks>
            次の値のみの種類がサポートされて: byte、sbyte、char、short、ushort、int、uint、long、ulong、float、double、decimal、bool、Guid、文字列、Uri、DateTime、DateTimeOffset、TimeSpan、ストリーム、byte[]、および IList の IDictionary には、種類がサポートされています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返信するキューのアドレス
            </summary>
        <value>返信するキューのアドレス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            返信するセッション識別子です。
            </summary>
        <value>返信するセッション識別子です。</value>
        <remarks>ReplyToSessionId の最大サイズは 128 です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            セッションの識別子です。
            </summary>
        <value>セッション識別子。</value>
        <remarks>SessionId の最大サイズは、128 文字です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.CorrelationFilter.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            送信先アドレス
            </summary>
        <value>送信するアドレス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.CorrelationFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="correlationFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のインスタンスの値を等価の文字列形式に変換します。
            </summary>
        <returns>現在のインスタンスの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>