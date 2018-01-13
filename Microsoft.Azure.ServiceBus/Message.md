<Type Name="Message" FullName="Microsoft.Azure.ServiceBus.Message">
  <TypeSignature Language="C#" Value="public class Message" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Message extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message" />
  <TypeSignature Language="VB.NET" Value="Public Class Message" />
  <TypeSignature Language="F#" Value="type Message = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            メッセージ オブジェクトを通信し、Service Bus でデータを転送するために使用します。
            </summary>
    <remarks>
            メッセージの構造の詳細については、<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads">製品ドキュメント。</a></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいメッセージを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] body);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (body As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Message : byte[] -&gt; Microsoft.Azure.ServiceBus.Message" Usage="new Microsoft.Azure.ServiceBus.Message body" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="array" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="body">バイト単位でメッセージのペイロード</param>
        <summary>
            指定したペイロードから新しいメッセージを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public byte[] Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As Byte()" />
      <MemberSignature Language="F#" Value="member this.Body : byte[] with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージの本文を取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            文字列から、新しいメッセージを作成する最も簡単な方法は次のです。
            <code>
            message.Body = System.Text.Encoding.UTF8.GetBytes("Message1");
            </code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.ServiceBus.Message Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Message" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.ServiceBus.Message" Usage="message.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>既に受信済みメッセージの複製を新しいメッセージとして送信することができるように、メッセージのクローンを作成します。 元のメッセージのシステムのプロパティはコピーされません。</summary>
        <returns>複製された<see cref="T:Microsoft.Azure.ServiceBus.Message" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはコンテンツ tpye 記述子を設定します。</summary>
        <value>RFC2045 コンテンツの種類の記述子。</value>
        <remarks>
              必要に応じて RFC2045、セクション 5、たとえば"application/json と"の形式に従って記述子を使用して、メッセージのペイロードを説明します。
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定の相関 id です。</summary>
        <value>相関関係の識別子です。</value>
        <remarks>
               により、アプリケーションの例は、返信があった場合に、メッセージの MessageId を反映の相関関係のため、メッセージのコンテキストを指定します。
               参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a>です。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterErrorDescriptionHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterErrorDescriptionHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterErrorDescriptionHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterErrorDescriptionHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterErrorDescriptionHeader" />
      <MemberType>Field</MemberType>
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
            エンティティの配信不能サブキューからメッセージを受信すると、詳細なエラーの説明を表すユーザー プロパティのキー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterReasonHeader">
      <MemberSignature Language="C#" Value="public static string DeadLetterReasonHeader;" />
      <MemberSignature Language="ILAsm" Value=".field public static string DeadLetterReasonHeader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberSignature Language="VB.NET" Value="Public Shared DeadLetterReasonHeader As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DeadLetterReasonHeader : string" Usage="Microsoft.Azure.ServiceBus.Message.DeadLetterReasonHeader" />
      <MemberType>Field</MemberType>
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
            エンティティの配信不能サブキューからメッセージが受信したときに、配信不能の理由を表すユーザー プロパティのキーです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</summary>
        <value>メッセージの有効期限刻 (utc)。 このプロパティは読み取り専用です。</value>
        <remarks>
             有効期限切れが原因でメッセージが削除対象としてマークされ、エンティティから取得できなくなった UTC 時刻。 有効期限はによって制御されます、<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />プロパティと、このプロパティから計算<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />+<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" /></remarks>
        <exception cref="T:System.InvalidOperationException">場合は、メッセージが受信されていません。 たとえばはまだ送信しない場合は、新しいメッセージが作成された場合や受信しています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはアプリケーション固有のラベルを設定します。</summary>
        <value>アプリケーション固有のラベル</value>
        <remarks>
              このプロパティを使用すると、アプリケーションは、電子メールの件名行と同様に標準化された方法でメッセージの目的を受信者に示すことができます。 マップされた AMQP プロパティは、「件名」です。
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメッセージを識別するメッセージ Id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
               メッセージ識別子は、アプリケーションによって定義される、メッセージとそのペイロードを一意に識別する値です。 この識別子は自由形式の文字列で、GUID またはアプリケーションのコンテキストから派生した識別子を反映することができます。 有効な場合、<a href="https://docs.microsoft.com/azure/service-bus-messaging/duplicate-detection">重複検出</a>機能を識別し、2 番目と同じ MessageId とメッセージの転送をさらに削除します。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはパーティション分割されたエンティティにメッセージを送信するためのパーティション キーを設定します。</summary>
        <value>パーティション キーです。 最大長は、128 文字です。</value>
        <remarks>
               <a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-partitioning">パーティション分割されたエンティティ</a>の場合、この値を設定すると、関連するメッセージを同じ内部パーティションに割り当てて、送信順序が正しく記録されるようにできます。 パーティションはハッシュ関数でこの値を介して選択され、直接選択することはできません。 セッションに対応するエンティティの場合、<see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />プロパティは、この値をオーバーライドします。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または応答を送信するエンティティのアドレスを設定します。</summary>
        <value>返信先エンティティのアドレス。</value>
        <remarks>
               これはアプリケーションによって定義される省略可能な値であり、メッセージの受信者への応答パスを表す標準的な方法です。 応答が必要な場合、送信者は、この値を応答の送信先にするキューまたはトピックの絶対または相対パスに設定します。
               参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a>です。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定のセッションの識別子の拡張、<see cref="P:Microsoft.Azure.ServiceBus.Message.ReplyTo" />アドレス。</summary>
        <value>セッションの識別子です。 最大長は、128 文字です。</value>
        <remarks>
               この値は、ReplyTo 情報を拡張しの応答を返信エンティティに送信されるときに設定されているセッション Id を指定します。 参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messages-payloads?#message-routing-and-correlation">メッセージのルーティングと相関関係</a></remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。 このプロパティは、UTC 時刻を返しますプロパティを設定するときに指定された DateTime 値もあります (utc)。</summary>
        <value>スケジュールされたエンキュー刻 (utc)。 この値では、遅延メッセージを送信するためです。
            後で、特定の時刻に送信するメッセージを遅延することを利用します。</value>
        <remarks> メッセージがエンキュー時間では、メッセージを同時に送信されることは限りません。 にキュー入れられたが取得されますが、実際の送信時間は、キューの作業負荷とその状態によって異なります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッションに対応するエンティティのセッション識別子を設定します。</summary>
        <value>セッション識別子。 最大長は、128 文字です。</value>
        <remarks>
               この値はアプリケーションによって定義され、セッションを認識するエンティティの場合に、メッセージのセッションへの所属を指定します。 同じセッション識別子を持つメッセージがまとめてロックされ、正確な順序での処理と多重化が可能になります。 セッションを認識しないエンティティの場合、この値は無視されます。
               参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-sessions">メッセージ セッション</a>です。
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.Azure.ServiceBus.Message.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージ本文の合計サイズをバイト単位で取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection SystemProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.Message/SystemPropertiesCollection SystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemProperties As Message.SystemPropertiesCollection" />
      <MemberSignature Language="F#" Value="member this.SystemProperties : Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" Usage="Microsoft.Azure.ServiceBus.Message.SystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />、システムによって設定されているプロパティの格納に使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Message.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメッセージの「有効期限の時間」の値を設定します。 
            </summary>
        <value>有効期限値、メッセージの時刻。</value>
        <remarks>
                この値は、メッセージの有効期限が切れるまでの相対期間は、メッセージの開始時点から開始がされて受け入れにキャプチャされるように、ブローカーによって格納されている<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />です。 ときに明示的に設定せず、想定した値は、それぞれのキューまたはトピックの DefaultTimeToLive です。 メッセージ レベル<see cref="P:Microsoft.Azure.ServiceBus.Message.TimeToLive" />値は、エンティティの DefaultTimeToLive 設定より長くすることはできませんし、それの場合は自動的に調整します。 参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-expiration">有効期限</a></remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または「を」アドレスを設定します。</summary>
        <value>「を」のアドレス。</value>
        <remarks>
               このプロパティはルーティング　シナリオでの将来の使用のために予約されており、現在はブローカー自体で無視されます。 アプリケーションは、この値を使用してルール主導で<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-auto-forwarding">自動順行連鎖</a>メッセージの目的の論理送信先を指定するシナリオです。
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="message.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のメッセージを表す文字列を返します。</summary>
        <returns>現在のメッセージの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; UserProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; UserProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.UserProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.Message.UserProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            カスタム メッセージのメタデータを使用できる ユーザーのプロパティ"バッグを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            次の値のみの種類がサポートされて: byte、sbyte、char、short、ushort、int、uint、long、ulong、float、double、decimal、bool、Guid、文字列、Uri、DateTime、DateTimeOffset、TimeSpan、ストリーム、byte[]、および IList の IDictionary には、種類がサポートされています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.Azure.ServiceBus.Message.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはパーティションの転送キュー経由でのエンティティにメッセージを送信するためのパーティション キーを設定します。</summary>
        <value>パーティション キーです。 最大長は、128 文字です。 </value>
        <remarks>
               この値が転送キュー パーティションを選択して、トランザクションのスコープ内の転送キュー経由でメッセージを送信する場合: これは機能的に等価<see cref="P:Microsoft.Azure.ServiceBus.Message.PartitionKey" />してメッセージに格納されている同時に、順序で転送されるようになります。
               参照してください<a href="https://docs.microsoft.com/azure/service-bus-messaging/service-bus-transactions#transfers-and-send-via">転送し、経由で送信</a>です。
               </remarks>
      </Docs>
    </Member>
  </Members>
</Type>