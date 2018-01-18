<Type Name="ISubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription">
  <TypeSignature Language="C#" Value="public interface ISubscription : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscription implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscription&#xA;Implements IGroupableResource(Of IServiceBusManager, SubscriptionInner), IHasInner(Of SubscriptionInner), IHasManager(Of IServiceBusManager), IIndependentChild(Of IServiceBusManager), IIndependentChildResource(Of IServiceBusManager, SubscriptionInner), IRefreshable(Of ISubscription), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ISubscription = interface&#xA;    interface IIndependentChildResource&lt;IServiceBusManager, SubscriptionInner&gt;&#xA;    interface IGroupableResource&lt;IServiceBusManager, SubscriptionInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;SubscriptionInner&gt;&#xA;    interface IIndependentChild&lt;IServiceBusManager&gt;&#xA;    interface IRefreshable&lt;ISubscription&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a9270-101">サービス バス トピック サブスクリプションを表す型。</span><span class="sxs-lookup"><span data-stu-id="a9270-101">Type representing service bus topic subscription.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="a9270-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="a9270-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-103">このサブスクリプションの受信要求があった最後の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-103">Gets last time there was a receive request to this subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-104">サブスクリプションのアクティブなメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-104">Gets number of active messages in the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-105">メッセージが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-105">Gets the exact time the message was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-106">サブスクリプションの配信不能メッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-106">Gets number of messages in the dead-letter subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTtlDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTtlDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTtlDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DefaultMessageTtlDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMessageTtlDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTtlDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DefaultMessageTtlDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-107">サブスクリプションへのメッセージの送信時から開始メッセージが切れるまでの期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-107">Gets the duration after which the message expires, starting from when the message is sent to subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public long DeleteOnIdleDurationInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteOnIdleDurationInMinutes As Long" />
      <MemberSignature Language="F#" Value="member this.DeleteOnIdleDurationInMinutes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.DeleteOnIdleDurationInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-108">その後、サブスクリプションは自動的に削除アイドル状態の期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-108">Gets the idle duration after which the subscription is automatically deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBatchedOperationsEnabled">
      <MemberSignature Language="C#" Value="public bool IsBatchedOperationsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBatchedOperationsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsBatchedOperationsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBatchedOperationsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBatchedOperationsEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsBatchedOperationsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-109">取得では、サーバー側のバッチ操作が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a9270-109">Gets indicates whether server-side batched operations are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeadLetteringEnabledForExpiredMessages">
      <MemberSignature Language="C#" Value="public bool IsDeadLetteringEnabledForExpiredMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDeadLetteringEnabledForExpiredMessages As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDeadLetteringEnabledForExpiredMessages : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-110">取得では、メッセージの有効期限が切れるときに、このサブスクリプションで配信不能サポートを持つかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a9270-110">Gets indicates whether this subscription has dead letter support when a message expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeadLetteringEnabledForFilterEvaluationFailedMessages">
      <MemberSignature Language="C#" Value="public bool IsDeadLetteringEnabledForFilterEvaluationFailedMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDeadLetteringEnabledForFilterEvaluationFailedMessages As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDeadLetteringEnabledForFilterEvaluationFailedMessages : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsDeadLetteringEnabledForFilterEvaluationFailedMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-111">取得では、サブスクリプションがフィルター評価例外ではサポート停止している文字を持つかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a9270-111">Gets indicates whether subscription has dead letter support on filter evaluation exceptions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSessionEnabled">
      <MemberSignature Language="C#" Value="public bool IsSessionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSessionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsSessionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSessionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSessionEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.IsSessionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-112">取得では、サブスクリプションがセッションをサポートするかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="a9270-112">Gets indicates whether the subscription supports sessions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDurationInSeconds">
      <MemberSignature Language="C#" Value="public long LockDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LockDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.LockDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LockDurationInSeconds : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.LockDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-113">これは、メッセージが他の受信者に対してロックされている時間のピーク ロックの期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-113">Gets the duration of peek-lock which is the amount of time that the message is locked for other receivers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCountBeforeDeadLetteringMessage">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCountBeforeDeadLetteringMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDeliveryCountBeforeDeadLetteringMessage As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCountBeforeDeadLetteringMessage : int" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-114">配信不能に移動としてマークする前に、メッセージ配信の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-114">Gets the maximum number of a message delivery before marking it as dead-lettered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-115">サブスクリプション内のメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-115">Gets the number of messages in the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-116">まだ消費にリリースするされていないサブスクリプションに送信されたメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-116">Gets number of messages sent to the subscription that are yet to be released for consumption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-117">サブスクリプションの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-117">Gets the current status of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-118">メッセージの数を取得は、配信不能メッセージに転送されます。</span><span class="sxs-lookup"><span data-stu-id="a9270-118">Gets number of messages transferred into dead letters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-119">メッセージの数を取得は、別のキュー、トピック、またはサブスクリプションに転送されます。</span><span class="sxs-lookup"><span data-stu-id="a9270-119">Gets number of messages transferred to another queue, topic, or subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9270-120">メッセージが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9270-120">Gets the exact time the message was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>