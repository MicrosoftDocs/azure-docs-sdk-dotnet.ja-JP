<Type Name="ITopic" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic">
  <TypeSignature Language="C#" Value="public interface ITopic : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ITopic&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITopic implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.ITopic&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITopic&#xA;Implements IGroupableResource(Of IServiceBusManager, TopicInner), IHasInner(Of TopicInner), IHasManager(Of IServiceBusManager), IIndependentChild(Of IServiceBusManager), IIndependentChildResource(Of IServiceBusManager, TopicInner), IRefreshable(Of ITopic), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ITopic = interface&#xA;    interface IIndependentChildResource&lt;IServiceBusManager, TopicInner&gt;&#xA;    interface IGroupableResource&lt;IServiceBusManager, TopicInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;TopicInner&gt;&#xA;    interface IIndependentChild&lt;IServiceBusManager&gt;&#xA;    interface IRefreshable&lt;ITopic&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.TopicInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.ITopic&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c6a30-101">Service Bus のトピックを表す型。</span><span class="sxs-lookup"><span data-stu-id="c6a30-101">Type representing Service Bus topic.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="c6a30-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="c6a30-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.AccessedAt" />
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
            <span data-ttu-id="c6a30-103">メッセージの最後の時刻を取得しますが送信すると、または、前回の要求がありました受信このトピックの内容にします。</span><span class="sxs-lookup"><span data-stu-id="c6a30-103">Gets last time a message was sent, or the last time there was a receive request to this topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.ActiveMessageCount" />
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
            <span data-ttu-id="c6a30-104">トピックのアクティブなメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-104">Gets number of active messages in the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ITopicAuthorizationRules AuthorizationRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.ITopicAuthorizationRules AuthorizationRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.AuthorizationRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationRules As ITopicAuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.AuthorizationRules : Microsoft.Azure.Management.ServiceBus.Fluent.ITopicAuthorizationRules" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.AuthorizationRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ITopicAuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6a30-105">Service Bus トピックの承認規則を管理するエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-105">Gets entry point to manage authorization rules for the Service Bus topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.CreatedAt" />
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
            <span data-ttu-id="c6a30-106">トピックが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-106">Gets the exact time the topic was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentSizeInBytes">
      <MemberSignature Language="C#" Value="public long CurrentSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.CurrentSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentSizeInBytes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.CurrentSizeInBytes" />
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
            <span data-ttu-id="c6a30-107">トピックの現在のサイズをバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-107">Gets current size of the topic, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DeadLetterMessageCount" />
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
            <span data-ttu-id="c6a30-108">配信不能メッセージ トピック内のメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-108">Gets number of messages in the dead-letter topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTtlDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTtlDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTtlDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DefaultMessageTtlDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMessageTtlDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTtlDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DefaultMessageTtlDuration" />
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
            <span data-ttu-id="c6a30-109">トピックへのメッセージの送信時から開始メッセージが切れるまでの期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-109">Gets the duration after which the message expires, starting from when the message is sent to topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public long DeleteOnIdleDurationInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteOnIdleDurationInMinutes As Long" />
      <MemberSignature Language="F#" Value="member this.DeleteOnIdleDurationInMinutes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DeleteOnIdleDurationInMinutes" />
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
            <span data-ttu-id="c6a30-110">トピックは自動的に削除するまでのアイドル期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-110">Gets the idle duration after which the topic is automatically deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateMessageDetectionHistoryDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateMessageDetectionHistoryDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateMessageDetectionHistoryDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DuplicateMessageDetectionHistoryDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DuplicateMessageDetectionHistoryDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateMessageDetectionHistoryDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.DuplicateMessageDetectionHistoryDuration" />
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
            <span data-ttu-id="c6a30-111">重複データ検出の履歴の期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-111">Gets the duration of the duplicate detection history.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBatchedOperationsEnabled">
      <MemberSignature Language="C#" Value="public bool IsBatchedOperationsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBatchedOperationsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsBatchedOperationsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBatchedOperationsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBatchedOperationsEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsBatchedOperationsEnabled" />
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
            <span data-ttu-id="c6a30-112">取得では、サーバー側のバッチ操作が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-112">Gets indicates whether server-side batched operations are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDuplicateDetectionEnabled">
      <MemberSignature Language="C#" Value="public bool IsDuplicateDetectionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDuplicateDetectionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsDuplicateDetectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDuplicateDetectionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDuplicateDetectionEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsDuplicateDetectionEnabled" />
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
            <span data-ttu-id="c6a30-113">取得では、このトピックの内容が重複データ検出を必要かどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-113">Gets indicates if this topic requires duplicate detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpressEnabled">
      <MemberSignature Language="C#" Value="public bool IsExpressEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpressEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsExpressEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpressEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpressEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsExpressEnabled" />
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
            <span data-ttu-id="c6a30-114">取得では、エクスプレス エンティティが有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-114">Gets indicates whether express entities are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPartitioningEnabled">
      <MemberSignature Language="C#" Value="public bool IsPartitioningEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPartitioningEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsPartitioningEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPartitioningEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPartitioningEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.IsPartitioningEnabled" />
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
            <span data-ttu-id="c6a30-115">取得では、トピックは、複数のメッセージ ブローカーにわたって分割するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-115">Gets indicates whether the topic is to be partitioned across multiple message brokers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMB">
      <MemberSignature Language="C#" Value="public long MaxSizeInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.MaxSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSizeInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMB : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.MaxSizeInMB" />
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
            <span data-ttu-id="c6a30-116">トピックに対して、メガバイト単位で割り当てられたメモリの最大サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-116">Gets the maximum size of memory allocated for the topic in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.ScheduledMessageCount" />
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
            <span data-ttu-id="c6a30-117">使用するために解放するのにはまだ、トピックに送信されたメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-117">Gets number of messages sent to the topic that are yet to be released for consumption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.Status" />
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
            <span data-ttu-id="c6a30-118">トピックの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-118">Gets the current status of the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public int SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : int" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.SubscriptionCount" />
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
            <span data-ttu-id="c6a30-119">トピックに対するサブスクリプションの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-119">Gets number of subscriptions for the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscriptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptions Subscriptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptions Subscriptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.Subscriptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscriptions As ISubscriptions" />
      <MemberSignature Language="F#" Value="member this.Subscriptions : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptions" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.Subscriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6a30-120">トピックに関連付けられているサブスクリプションを管理するエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-120">Gets entry point to manage subscriptions associated with the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.TransferDeadLetterMessageCount" />
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
            <span data-ttu-id="c6a30-121">メッセージの数を取得は、配信不能メッセージに転送されます。</span><span class="sxs-lookup"><span data-stu-id="c6a30-121">Gets number of messages transferred into dead letters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.TransferMessageCount" />
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
            <span data-ttu-id="c6a30-122">メッセージの数を取得は、別のトピック、トピック、またはサブスクリプションに転送されます。</span><span class="sxs-lookup"><span data-stu-id="c6a30-122">Gets number of messages transferred to another topic, topic, or subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ITopic.UpdatedAt" />
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
            <span data-ttu-id="c6a30-123">トピックが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a30-123">Gets the exact time the topic was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>