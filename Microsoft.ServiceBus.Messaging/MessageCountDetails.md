<Type Name="MessageCountDetails" FullName="Microsoft.ServiceBus.Messaging.MessageCountDetails">
  <TypeSignature Language="C#" Value="public sealed class MessageCountDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageCountDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageCountDetails" />
  <TypeSignature Language="F#" Value="type MessageCountDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MessageCountDetails", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="7598a-101">このクラスには、プライマリのメッセージング エンティティ (キュー、トピック、サブスクリプション) のサブキューからメッセージの詳細を取得することができるようにするプロパティが含まれています。</span><span class="sxs-lookup"><span data-stu-id="7598a-101">This class contains properties that enable you to retrieve details of messages from sub-queues of primary messaging entities (queues, topics, subscriptions).</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7598a-102"><see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7598a-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageCountDetails (long activeMessageCount, long deadletterMessageCount, long scheduledMessageCount, long transferMessageCount, long transferDlqMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 activeMessageCount, int64 deadletterMessageCount, int64 scheduledMessageCount, int64 transferMessageCount, int64 transferDlqMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageCountDetails.#ctor(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (activeMessageCount As Long, deadletterMessageCount As Long, scheduledMessageCount As Long, transferMessageCount As Long, transferDlqMessageCount As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessageCountDetails : int64 * int64 * int64 * int64 * int64 -&gt; Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="new Microsoft.ServiceBus.Messaging.MessageCountDetails (activeMessageCount, deadletterMessageCount, scheduledMessageCount, transferMessageCount, transferDlqMessageCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="activeMessageCount" Type="System.Int64" />
        <Parameter Name="deadletterMessageCount" Type="System.Int64" />
        <Parameter Name="scheduledMessageCount" Type="System.Int64" />
        <Parameter Name="transferMessageCount" Type="System.Int64" />
        <Parameter Name="transferDlqMessageCount" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="activeMessageCount"><span data-ttu-id="7598a-103">アクティブなメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="7598a-103">The number of active messages.</span></span></param>
        <param name="deadletterMessageCount"><span data-ttu-id="7598a-104">配信不能メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="7598a-104">The number of dead letters.</span></span></param>
        <param name="scheduledMessageCount"><span data-ttu-id="7598a-105">スケジュールされたメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="7598a-105">The number of scheduled messages.</span></span></param>
        <param name="transferMessageCount"><span data-ttu-id="7598a-106">メッセージの数は、その他のキュー、サブスクリプション、またはトピックに転送されます。</span><span class="sxs-lookup"><span data-stu-id="7598a-106">The number of messages transferred to other queues, subscriptions, or topics.</span></span></param>
        <param name="transferDlqMessageCount"><span data-ttu-id="7598a-107">メッセージの数は、配信不能キューに転送されます。</span><span class="sxs-lookup"><span data-stu-id="7598a-107">The number of messages transferred to the dead letter queue.</span></span></param>
        <summary><span data-ttu-id="7598a-108">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />アクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージ、メッセージの数を持つクラスが他のキュー、サブスクリプション、またはトピックに転送され、メッセージの数が配信不能キューに転送します。</span><span class="sxs-lookup"><span data-stu-id="7598a-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> class with the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7598a-109">取得またはキュー、トピック、またはサブスクリプションのアクティブなメッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-109">Gets or sets the number of active messages in the queue, topic, or subscription.</span></span></summary>
        <value><span data-ttu-id="7598a-110">返します<see cref="T:System.Int64" />アクティブなメッセージの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-110">Returns <see cref="T:System.Int64" /> that specifies the number of active messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7598a-111">取得または配信不能メッセージのメッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-111">Gets or sets the number of messages that are dead letters.</span></span></summary>
        <value><span data-ttu-id="7598a-112">返します<see cref="T:System.Int64" />配信不能メッセージのメッセージの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-112">Returns <see cref="T:System.Int64" />that specifies the number of messages that are dead letters.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65539)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7598a-113">取得または番号のスケジュールされたメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-113">Gets or sets the number scheduled messages.</span></span></summary>
        <value><span data-ttu-id="7598a-114">返します<see cref="T:System.Int64" />スケジュールされたメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="7598a-114">Returns <see cref="T:System.Int64" />the number of scheduled messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65541)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7598a-115">取得または数値に文字を配信不能に転送されるメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-115">Gets or sets the number messages transferred into dead letters.</span></span></summary>
        <value><span data-ttu-id="7598a-116">返します<see cref="T:System.Int64" />番号に文字を配信不能に転送されるメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-116">Returns <see cref="T:System.Int64" />that specifies the number messages transferred into dead letters.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.MessageCountDetails.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Order=65540)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7598a-117">取得または別のキュー、トピック、またはサブスクリプションに転送されるメッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-117">Gets or sets the number of messages transferred to another queue, topic, or subscription.</span></span></summary>
        <value><span data-ttu-id="7598a-118">返します<see cref="T:System.Int64" />別のキュー、トピック、またはサブスクリプションに転送されるメッセージの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="7598a-118">Returns <see cref="T:System.Int64" />that specifies the number of messages transferred to another queue, topic, or subscription</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>