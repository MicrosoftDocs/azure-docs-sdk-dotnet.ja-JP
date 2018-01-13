<Type Name="SubscriptionDescription" FullName="Microsoft.ServiceBus.Messaging.SubscriptionDescription">
  <TypeSignature Language="C#" Value="public sealed class SubscriptionDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SubscriptionDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SubscriptionDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type SubscriptionDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SubscriptionDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>サブスクリプションの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDescription (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (topicPath As String, subscriptionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SubscriptionDescription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="new Microsoft.ServiceBus.Messaging.SubscriptionDescription (topicPath, subscriptionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">トピックのパスです。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このサブスクリプションの受信要求が、最終時刻を取得します。</summary>
        <value>最後がこのサブスクリプションの受信要求します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />アイドル状態の間隔がその後、サブスクリプションは自動的に削除します。 最小時間は、5 分です。</summary>
        <value>サブスクリプションのアイドル時間の範囲の自動削除します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージング エンティティの可用性の状態を取得します。</summary>
        <value>メッセージング エンティティの可用性の状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが作成された正確な時刻を取得します。</summary>
        <value>メッセージが作成された時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または既定メッセージの time to live の値を設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、既定値が使用されるときに<see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />メッセージ自体に設定されていません。その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。 サブスクライバーは期限切れのメッセージを受信することができません。メッセージできます、TimeToLive 値より小さく、ここで指定されているが、既定で、TimeToLive に設定されて<see cref="F:System.TimeSpan.MaxValue" />です。 そのため、このプロパティは、有効期限の値をメッセージに適用される既定の時間になります。</summary>
        <value>サブスクリプションの有効期限の既定のメッセージ時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはバッチの操作が有効になっているかどうかを示す値を設定します。</summary>
        <value>バッチ操作が有効な場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnFilterEvaluationExceptions">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnFilterEvaluationExceptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnFilterEvaluationExceptions As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnFilterEvaluationExceptions : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサブスクリプションがフィルター評価例外ではサポート停止している文字がかどうかを示す値を設定します。</summary>
        <value>true の場合、サブスクリプションがフィルター評価例外ではサポート停止している文字それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサブスクリプションがメッセージの有効期限が切れるときに、配信不能サポートがかどうかを示す値を設定します。</summary>
        <value>true がある場合、メッセージの配信不能メッセージのサポートをサブスクリプションを期限切れです。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはデッド文字のメッセージを転送する、受信者へのパスを設定します。</summary>
        <value>デッド文字のメッセージを転送する受信者へのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージが転送される受信者へのパスを設定します。</summary>
        <value>メッセージが転送される受信者へのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、ロック期間の期間サブスクリプション。</summary>
        <value>ロック期間は、サブスクリプションを期間します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または最大配信回数を設定します。</summary>
        <value>最大配信回数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージの数を取得します。</summary>
        <value>メッセージ数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サブスクリプションに関するメッセージの詳細を取得します。</summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />アクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージの数、メッセージと転送されるその他のキュー、サブスクリプション、またはトピックについては、メッセージの数が配信不能キューに転送します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
              メッセージの time to live の既定値
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サブスクリプションの説明の名前を取得します。</summary>
        <value>サブスクリプションの説明の名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサブスクリプションがセッションの概念をサポートしているかを示す値を設定します。</summary>
        <value>受信側のアプリケーションを使用してキューからのみ受信できる場合は true、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />を使用してキューを利用できない場合は false です。<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサブスクリプション (有効または無効になっている) の現在の状態を設定します。 エンティティを無効にすると、そのエンティティが送信またはメッセージを受信できません。</summary>
        <value>サブスクリプションの現在の状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このサブスクリプションの説明が属するトピックのパスを取得します。</summary>
        <value>このサブスクリプションの説明が属するトピックのパス。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージが更新された正確な時刻を取得します。</summary>
        <value>メッセージが更新された時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはユーザーのメタデータを設定します。</summary>
        <value>ユーザーのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>