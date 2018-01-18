<Type Name="EventHubStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class EventHubStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type EventHubStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ServiceBus/EventHub")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="de398-101">ストリーム データを含む Event Hub 入力データ ソースについて説明します。</span><span class="sxs-lookup"><span data-stu-id="de398-101">Describes an Event Hub input data source that contains stream data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de398-102">EventHubStreamInputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de398-102">Initializes a new instance of the EventHubStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubStreamInputDataSource (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string eventHubName = null, string consumerGroupName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string eventHubName, string consumerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional eventHubName As String = null, Optional consumerGroupName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, eventHubName, consumerGroupName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace"><span data-ttu-id="de398-103">目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-103">The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyName"><span data-ttu-id="de398-104">イベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシーの名前。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-104">The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyKey"><span data-ttu-id="de398-105">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。</span><span class="sxs-lookup"><span data-stu-id="de398-105">The shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="de398-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="eventHubName"><span data-ttu-id="de398-107">イベント ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="de398-107">The name of the Event Hub.</span></span> <span data-ttu-id="de398-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="de398-109">Event Hub からイベントを読み取るために使用する必要があります、イベント ハブ コンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de398-109">The name of an Event Hub Consumer Group that should be used to read events from the Event Hub.</span></span>
            <span data-ttu-id="de398-110">複数の入力に対して個別のコンシューマー グループ名を指定すると、これらの各入力、Event Hub から同じイベントを受信することをによりします。</span><span class="sxs-lookup"><span data-stu-id="de398-110">Specifying distinct consumer group names for multiple inputs allows each of those inputs to receive the same events from the Event Hub.</span></span>
            <span data-ttu-id="de398-111">指定しない場合、入力は、イベント ハブの既定のコンシューマー グループを使用します。</span><span class="sxs-lookup"><span data-stu-id="de398-111">If not specified, the input uses the Event Hub’s default consumer group.</span></span></param>
        <summary>
            <span data-ttu-id="de398-112">EventHubStreamInputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de398-112">Initializes a new instance of the EventHubStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consumerGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de398-113">取得または Event Hub からイベントを読み取るために使用する必要があります、イベント ハブ コンシューマー グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="de398-113">Gets or sets the name of an Event Hub Consumer Group that should be used to read events from the Event Hub.</span></span> <span data-ttu-id="de398-114">複数の入力に対して個別のコンシューマー グループ名を指定すると、これらの各入力、Event Hub から同じイベントを受信することをによりします。</span><span class="sxs-lookup"><span data-stu-id="de398-114">Specifying distinct consumer group names for multiple inputs allows each of those inputs to receive the same events from the Event Hub.</span></span> <span data-ttu-id="de398-115">指定しない場合、入力は、イベント ハブの既定のコンシューマー グループを使用します。</span><span class="sxs-lookup"><span data-stu-id="de398-115">If not specified, the input uses the Event Hub’s default consumer group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventHubName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de398-116">取得またはイベント ハブの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="de398-116">Gets or sets the name of the Event Hub.</span></span> <span data-ttu-id="de398-117">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-117">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de398-118">取得または目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間を設定します。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-118">Gets or sets the namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.SharedAccessPolicyKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de398-119">取得または指定した共有アクセス ポリシーの共有アクセス ポリシーのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="de398-119">Gets or sets the shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="de398-120">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-120">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyName">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubStreamInputDataSource.SharedAccessPolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de398-121">取得またはイベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシー名を設定します。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="de398-121">Gets or sets the shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>