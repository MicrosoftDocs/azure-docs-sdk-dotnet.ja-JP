<Type Name="TopicDescription" FullName="Microsoft.ServiceBus.Messaging.TopicDescription">
  <TypeSignature Language="C#" Value="public sealed class TopicDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TopicDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TopicDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type TopicDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="TopicDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>トピックの説明を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.TopicDescription : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="new Microsoft.ServiceBus.Messaging.TopicDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />指定された相対パスを持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージをトピックに最後に送信された日付と時刻を取得します。</summary>
        <value>日付と時刻をメッセージが送信された前回のトピックにします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>説明の承認規則を取得します。</summary>
        <value>説明の承認規則。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />トピックは自動的に削除するまでアイドル状態の間隔。 最小時間は、5 分です。</summary>
        <value>トピックのアイドル時間の範囲の自動削除します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このインスタンスの可用性の状態を取得します。</summary>
        <value>このインスタンスの可用性の状態です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トピックが作成された日付と時刻を取得します。</summary>
        <value>トピックが作成された日付と時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または既定メッセージの time to live のトピックの値を設定します。 これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。 これは、既定値が使用されるときに<see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />メッセージ自体に設定されていません。その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。 サブスクライバーは期限切れのメッセージを受信することができません。</summary>
        <value>トピックの有効期限の既定のメッセージ時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />重複データ検出の履歴の期間を定義する構造体。</summary>
        <value><see cref="T:System.TimeSpan" />重複データ検出の履歴の期間を定義する構造体。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
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
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Express のエンティティが有効になっているかどうかを示す値を設定します。 高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</summary>
        <value>エクスプレス エンティティが有効な場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFilteringMessagesBeforePublishing">
      <MemberSignature Language="C#" Value="public bool EnableFilteringMessagesBeforePublishing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFilteringMessagesBeforePublishing As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableFilteringMessagesBeforePublishing : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはパブリッシュする前に、メッセージをフィルター処理する必要かどうかを設定します。</summary>
        <value>パブリッシュする前にメッセージのフィルター処理が有効になっている場合は true。それ以外の場合は false です。</value>
        <remarks> この機能は開発およびテスト目的でのみ使用することをお勧めします。  
            たとえば、トピックに新しいルールやフィルターが追加されて、ときにこの機能は新しいフィルター式が期待どおりに動作していることを確認する使用できます。 テストおよびと正常に動作して、機能は実稼働環境でオフにする必要があります。 </remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException">サブスクリプションが一致しない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または複数のメッセージ ブローカーにわたって分割するトピックを有効にするかどうかを設定します。 高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</summary>
        <value>複数のメッセージ ブローカーにわたって分割するトピックを有効にする場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>匿名アクセスが許可されているかどうかを取得します。</summary>
        <value>匿名アクセスが許可されている以外の場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトピックに割り当てられたメモリのサイズはメガバイト単位で、このトピックの最大サイズを設定します。</summary>
        <value>最大サイズ (メガバイト単位)。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このトピックに関するメッセージの詳細を取得します。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />数を格納しているアクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージの場合は、他のキュー、サブスクリプション、またはトピックについてにメッセージが転送され、メッセージの数が配信不能キューに転送します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
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
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トピックのパスを取得します。</summary>
        <value>トピックのパス。</value>
        <remarks>
              これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトピックに重複データ検出が必要とするかどうかを示す値を設定します。</summary>
        <value>トピックには、重複データ検出; が必要な場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トピックのサイズをバイト単位で取得します。</summary>
        <value>(バイト単位) のトピックのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定 (有効または無効になっています)、このトピックの現在の状態。 エンティティを無効にすると、そのエンティティが送信またはメッセージを受信できません。</summary>
        <value>トピックの状態です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public int SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : int" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得してから、サブスクリプションの数。</summary>
        <value><see cref="T:System.Int32" />サブスクリプションの数を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメソッドを順序付けのサポートを設定します。</summary>
        <value>メソッドを順序付けのサポート。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トピックが更新された日付と時刻を取得します。</summary>
        <value>トピックが更新された日付と時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または説明に関連付けられているユーザーのメタデータを設定します。</summary>
        <value>説明に関連付けられているユーザーのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>