<Type Name="BrokeredMessageProperty" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessageProperty : System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessageProperty extends System.Object implements class System.ServiceModel.Channels.IMessageProperty" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessageProperty&#xA;Implements IMessageProperty" />
  <TypeSignature Language="F#" Value="type BrokeredMessageProperty = class&#xA;    interface IMessageProperty" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IMessageProperty</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>プロパティ バッグを表す、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessageProperty ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはコンテンツの種類を設定します。</summary>
        <value>メッセージ本文のコンテンツの種類。 これは、送信者と受信者のアプリケーション固有のロジックで使用されるコンテンツの種類の識別子です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定の相関関係の識別子。</summary>
        <value>相関関係の識別子です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このメッセージの配信に加えられた配信の数を取得します。</summary>
        <value>このメッセージの配信に加えられた配送の数。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.InvalidOperationException">ServiceBus によってメッセージが配信されていない場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または送信時刻の日時を UTC に設定します。</summary>
        <value>エンキュー刻 (utc)。 この値は、メッセージをエンキューの実際の時間を表します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが期限切れに設定されている UTC の日付と時刻を取得します。</summary>
        <value>メッセージの有効期限刻 (utc)。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのプロパティを永続化を強制するかどうかを設定します。</summary>
        <value>このプロパティに永続化を強制する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはアプリケーション固有のラベルを設定します。</summary>
        <value>アプリケーション固有のラベル。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</summary>
        <value>日時キュー/サブスクリプションになるまで、メッセージがロックされます。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、ServiceBus からメッセージを受信しませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Service Bus によってメッセージに割り当てられたロック トークンを取得します。</summary>
        <value>Service Bus によってメッセージに割り当てられたロック トークンです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、ServiceBus からメッセージを受信しませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>仲介型メッセージを取得します。</summary>
        <value>仲介型メッセージ オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの識別子を設定します。</summary>
        <value>メッセージ ID。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.ArgumentException">場合はメッセージ id が null であるか、長さは 128 文字を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public static readonly string Name;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string Name" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Name As String " />
      <MemberSignature Language="F#" Value=" staticval mutable Name : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Name" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティ バッグを適用するために使用される名前、<see cref="T:System.ServiceModel.Channels.Message" />メッセージを送信するときにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定に、キューまたはトピックをセッション対応していないトランザクション メッセージを送信するためのパーティション キー。</summary>
        <value><see cref="T:System.String" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>仲介型メッセージのプロパティを取得します。</summary>
        <value>仲介型メッセージのプロパティです。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはに返信するキューのアドレスを設定します。</summary>
        <value>メッセージ キューのアドレスに返信します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定に返信するセッション識別子。</summary>
        <value>返信するセッション識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージがエンキューをいるを UTC で日付と時刻を設定します。</summary>
        <value>スケジュールされたエンキュー刻 (utc)。 この値では、遅延メッセージを送信するためです。 後で、特定の時刻に送信するメッセージを遅延することを利用します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">渡された値が場合 DateTime.MaxValue します。</exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Service Bus によってメッセージに割り当てられた一意の番号を取得します。</summary>
        <value>Service Bus によってメッセージに割り当てられた一意の番号。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、メッセージがメッセージ サーバーから受信しませんでした。</exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッションの識別子を設定します。</summary>
        <value>セッションの識別子。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IMessageProperty.CreateCopy">
      <MemberSignature Language="C#" Value="System.ServiceModel.Channels.IMessageProperty IMessageProperty.CreateCopy ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.ServiceModel.Channels.IMessageProperty System.ServiceModel.Channels.IMessageProperty.CreateCopy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.System#ServiceModel#Channels#IMessageProperty#CreateCopy" />
      <MemberSignature Language="VB.NET" Value="Function CreateCopy () As IMessageProperty Implements IMessageProperty.CreateCopy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.IMessageProperty.CreateCopy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IMessageProperty</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または有効期限値、メッセージの時刻を設定します。 その後、メッセージは期限切れから開始その TimeToLive の値が有効期限が切れるし、メッセージ ストアに保持されなくよりも古いサービス Bus.Messages にメッセージが送信される期間です。 サブスクライバーは期限切れのメッセージを受信することができません。</summary>
        <value>有効期限値、メッセージの時刻。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">渡された値が TimeSpan.Zero 小さい場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または送信をアドレスに設定します。</summary>
        <value>送信先キューのアドレス。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">場合は、メッセージは破棄された状態です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessageProperty.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトランザクションがある場合、転送キュー経由のメッセージを送信するために、パーティション キー値を設定します。</summary>
        <value><see cref="T:System.String" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>