<Type Name="QueueDescription" FullName="Microsoft.ServiceBus.Messaging.QueueDescription">
  <TypeSignature Language="C#" Value="public sealed class QueueDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type QueueDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="QueueDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>キューのメタデータの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.QueueDescription : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="new Microsoft.ServiceBus.Messaging.QueueDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />指定された相対パスを持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得、前回のメッセージが送信された、またはこのキューの受信要求が最後にします。</summary>
        <value>メッセージが送信された最後の時刻、またはこのキューの受信要求が最後にします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> を取得します。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />アイドル状態の間隔がその後、キューは自動的に削除します。 最小時間は、5 分です。</summary>
        <value>キューの長さはアイドル状態の自動削除します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キューのエンティティの可用性の状態を取得します。</summary>
        <value>キューのエンティティの可用性の状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.CreatedAt" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />
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
        <value>ライブの値に既定のメッセージ時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />重複データ検出の履歴の期間を定義する構造体。 既定値は、10 分です。</summary>
        <value><see cref="T:System.TimeSpan" />重複検出の履歴の時間枠を表す構造です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサーバー側のバッチ操作が有効になっているかどうかを示す値を設定します。</summary>
        <value>バッチ操作が有効な場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの有効期限が切れるときに、このキューに配信不能サポートを持つかどうかを示す値を設定します。</summary>
        <value>キューがメッセージの期限が切れたときに、配信不能サポートを持つ場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Express のエンティティが有効になっているかどうかを示す値を設定します。 エクスプレス キューでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</summary>
        <value>エクスプレス エンティティが有効な場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または複数のメッセージ ブローカーにわたって分割するキューが有効になっているかどうかを示す値を設定します。 </summary>
        <value>複数のメッセージ ブローカーにわたって分割するキューが有効である場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardDeadLetteredMessagesTo" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.ForwardTo" />
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
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、アクセス可能なメッセージが匿名かどうかを示す値を設定します。</summary>
        <value>true の場合は、メッセージは匿名アクセスできません。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定は、ピーク ロックの期間他の受信者に対してメッセージがロックされている時間の量は、します。 最大値<see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" />は 5 分です。 既定値は 1 分です。</summary>
        <value>ロックの期間です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または最大配信数を設定します。 メッセージは自動的に配信不能になりましたに配信したファイルの数です。</summary>
        <value>最大配信回数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキューに割り当てられたメモリのサイズであるキューの最大サイズをメガバイト単位で設定します。</summary>
        <value>メガバイト単位でキューの最大サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キュー内のメッセージの数を取得します。</summary>
        <value>メッセージ数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キューのメッセージの詳細を取得します。</summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />アクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージの数、メッセージと転送されるその他のキュー、サブスクリプション、またはトピックについては、メッセージの数が配信不能キューに転送します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.MessageTimeToLiveDefaultValue" />
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
              メッセージの time to live の既定値 (バイト単位)
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキューの名前を設定します。</summary>
        <value>キューの名前。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのキューに重複データ検出が必要かどうかを示す値を設定します。</summary>
        <value>このキューには、重複の検出が必要な場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキューがセッションの概念をサポートするかどうかを示す値を設定します。</summary>
        <value>受信側のアプリケーションを使用してキューからのみ受信できる場合は true、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />を使用してキューを利用できない場合は false です。<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>キューのサイズをバイト単位で取得します。</summary>
        <value>キューのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定 (有効または無効になっています)、キューの現在の状態。 エンティティを無効にすると、そのエンティティが送信またはメッセージを受信できません。</summary>
        <value>キューの現在の状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはキューが順序付けをサポートするかどうかを示す値を設定します。</summary>
        <value>キューが順序付け; をサポートしている場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UpdatedAt" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueDescription.UserMetadata" />
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