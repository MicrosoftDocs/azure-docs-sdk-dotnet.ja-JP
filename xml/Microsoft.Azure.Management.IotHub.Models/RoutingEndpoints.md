<Type Name="RoutingEndpoints" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints">
  <TypeSignature Language="C#" Value="public class RoutingEndpoints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingEndpoints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingEndpoints" />
  <TypeSignature Language="F#" Value="type RoutingEndpoints = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="394ab-101">IoT ハブがルーティング規則に基づいてメッセージをルーティングするカスタムのエンドポイントに関連するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="394ab-101">The properties related to the custom endpoints to which your IoT hub routes messages based on the routing rules.</span></span> <span data-ttu-id="394ab-102">有料のハブのすべてのエンドポイントの種類の 10 のカスタム エンドポイントの最大値が許可されているし、カスタム エンドポイントを 1 つだけが許可されたすべてのエンドポイントの種類は無料ハブ。</span><span class="sxs-lookup"><span data-stu-id="394ab-102">A maximum of 10 custom endpoints are allowed across all endpoint types for paid hubs and only 1 custom endpoint is allowed across all endpoint types for free hubs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="394ab-103">RoutingEndpoints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="394ab-103">Initializes a new instance of the RoutingEndpoints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEndpoints (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; serviceBusQueues = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; serviceBusTopics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; eventHubs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; storageContainers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; serviceBusQueues, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; serviceBusTopics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; eventHubs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; storageContainers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusQueues As IList(Of RoutingServiceBusQueueEndpointProperties) = null, Optional serviceBusTopics As IList(Of RoutingServiceBusTopicEndpointProperties) = null, Optional eventHubs As IList(Of RoutingEventHubProperties) = null, Optional storageContainers As IList(Of RoutingStorageContainerProperties) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints (serviceBusQueues, serviceBusTopics, eventHubs, storageContainers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusQueues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt;" />
        <Parameter Name="serviceBusTopics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt;" />
        <Parameter Name="eventHubs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt;" />
        <Parameter Name="storageContainers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceBusQueues"><span data-ttu-id="394ab-104">IoT hub では、メッセージがルーティング ルーティング ルールに基づいて Service Bus キューのエンドポイントのリスト。</span><span class="sxs-lookup"><span data-stu-id="394ab-104">The list of Service Bus queue endpoints that IoT hub routes the messages to, based on the routing rules.</span></span></param>
        <param name="serviceBusTopics"><span data-ttu-id="394ab-105">IoT hub は、メッセージをルーティングする Service Bus トピック エンドポイントの一覧は、ルーティングの規則に基づいています。</span><span class="sxs-lookup"><span data-stu-id="394ab-105">The list of Service Bus topic endpoints that the IoT hub routes the messages to, based on the routing rules.</span></span></param>
        <param name="eventHubs"><span data-ttu-id="394ab-106">IoT hub では、メッセージがルーティング ルーティング ルールに基づいて Event Hubs エンドポイントのリスト。</span><span class="sxs-lookup"><span data-stu-id="394ab-106">The list of Event Hubs endpoints that IoT hub routes messages to, based on the routing rules.</span></span> <span data-ttu-id="394ab-107">この一覧には、組み込みの Event Hubs エンドポイントは含まれません。</span><span class="sxs-lookup"><span data-stu-id="394ab-107">This list does not include the built-in Event Hubs endpoint.</span></span></param>
        <param name="storageContainers"><span data-ttu-id="394ab-108">IoT hub では、メッセージがルーティング ルーティング ルールに基づいてストレージ コンテナーのエンドポイントの一覧。</span><span class="sxs-lookup"><span data-stu-id="394ab-108">The list of storage container endpoints that IoT hub routes messages to, based on the routing rules.</span></span></param>
        <summary>
            <span data-ttu-id="394ab-109">RoutingEndpoints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="394ab-109">Initializes a new instance of the RoutingEndpoints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; EventHubs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; EventHubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.EventHubs" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubs As IList(Of RoutingEventHubProperties)" />
      <MemberSignature Language="F#" Value="member this.EventHubs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.EventHubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventHubs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394ab-110">取得または IoT ハブに、ルーティング ルールに基づいてメッセージをルーティングする Event Hubs のエンドポイントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="394ab-110">Gets or sets the list of Event Hubs endpoints that IoT hub routes messages to, based on the routing rules.</span></span> <span data-ttu-id="394ab-111">この一覧には、組み込みの Event Hubs エンドポイントは含まれません。</span><span class="sxs-lookup"><span data-stu-id="394ab-111">This list does not include the built-in Event Hubs endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; ServiceBusQueues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; ServiceBusQueues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusQueues" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusQueues As IList(Of RoutingServiceBusQueueEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.ServiceBusQueues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusQueues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceBusQueues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394ab-112">取得または IoT ハブに、ルーティング ルールに基づいてメッセージをルーティングする Service Bus キューのエンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="394ab-112">Gets or sets the list of Service Bus queue endpoints that IoT hub routes the messages to, based on the routing rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; ServiceBusTopics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; ServiceBusTopics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusTopics" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusTopics As IList(Of RoutingServiceBusTopicEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.ServiceBusTopics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusTopics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceBusTopics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394ab-113">取得または IoT hub は、ルーティング ルールに基づくにメッセージをルーティングする Service Bus トピック エンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="394ab-113">Gets or sets the list of Service Bus topic endpoints that the IoT hub routes the messages to, based on the routing rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; StorageContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; StorageContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.StorageContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageContainers As IList(Of RoutingStorageContainerProperties)" />
      <MemberSignature Language="F#" Value="member this.StorageContainers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.StorageContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="394ab-114">取得または IoT ハブに、ルーティング ルールに基づいてメッセージをルーティングするストレージ コンテナーのエンドポイントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="394ab-114">Gets or sets the list of storage container endpoints that IoT hub routes messages to, based on the routing rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>