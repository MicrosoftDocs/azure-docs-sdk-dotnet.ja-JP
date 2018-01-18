<Type Name="EventSubscription" FullName="Microsoft.Azure.Management.EventGrid.Models.EventSubscription">
  <TypeSignature Language="C#" Value="public class EventSubscription : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventSubscription extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Class EventSubscription&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type EventSubscription = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="279d9-101">イベント サブスクリプション</span><span class="sxs-lookup"><span data-stu-id="279d9-101">Event Subscription</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="279d9-102">EventSubscription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="279d9-102">Initializes a new instance of the EventSubscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscription (string id = null, string name = null, string type = null, string topic = null, string provisioningState = null, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination = null, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter = null, System.Collections.Generic.IList&lt;string&gt; labels = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string topic, string provisioningState, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter, class System.Collections.Generic.IList`1&lt;string&gt; labels) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional topic As String = null, Optional provisioningState As String = null, Optional destination As EventSubscriptionDestination = null, Optional filter As EventSubscriptionFilter = null, Optional labels As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventSubscription : string * string * string * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventSubscription (id, name, type, topic, provisioningState, destination, filter, labels)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="topic" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
        <Parameter Name="filter" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" />
        <Parameter Name="labels" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="279d9-103">リソースの完全修飾識別子</span><span class="sxs-lookup"><span data-stu-id="279d9-103">Fully qualified identifier of the resource</span></span></param>
        <param name="name"><span data-ttu-id="279d9-104">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="279d9-104">Name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="279d9-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="279d9-105">Type of the resource</span></span></param>
        <param name="topic"><span data-ttu-id="279d9-106">イベント サブスクリプションのトピックの名前です。</span><span class="sxs-lookup"><span data-stu-id="279d9-106">Name of the topic of the event subscription.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="279d9-107">イベント サブスクリプションの状態を準備しています。</span><span class="sxs-lookup"><span data-stu-id="279d9-107">Provisioning state of the event subscription.</span></span> <span data-ttu-id="279d9-108">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'</span><span class="sxs-lookup"><span data-stu-id="279d9-108">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span></param>
        <param name="destination"><span data-ttu-id="279d9-109">イベントがイベント サブスクリプションの配信にある転送先について説明します。</span><span class="sxs-lookup"><span data-stu-id="279d9-109">Information about the destination where events have to be delivered for the event subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="279d9-110">イベント サブスクリプションのフィルターに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="279d9-110">Information about the filter for the event subscription.</span></span></param>
        <param name="labels"><span data-ttu-id="279d9-111">ユーザーの一覧には、ラベルが定義されています。</span><span class="sxs-lookup"><span data-stu-id="279d9-111">List of user defined labels.</span></span></param>
        <summary>
            <span data-ttu-id="279d9-112">EventSubscription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="279d9-112">Initializes a new instance of the EventSubscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As EventSubscriptionDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="279d9-113">取得またはイベントがイベント サブスクリプションの配信にある転送先に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="279d9-113">Gets or sets information about the destination where events have to be delivered for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As EventSubscriptionFilter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="279d9-114">取得またはイベント サブスクリプションのフィルターに関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="279d9-114">Gets or sets information about the filter for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Labels">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Labels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Labels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Labels" />
      <MemberSignature Language="VB.NET" Value="Public Property Labels As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Labels : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Labels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.labels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="279d9-115">取得またはユーザー定義のラベルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="279d9-115">Gets or sets list of user defined labels.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="279d9-116">イベント サブスクリプションの状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="279d9-116">Gets provisioning state of the event subscription.</span></span> <span data-ttu-id="279d9-117">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'</span><span class="sxs-lookup"><span data-stu-id="279d9-117">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Topic">
      <MemberSignature Language="C#" Value="public string Topic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Topic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Topic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Topic As String" />
      <MemberSignature Language="F#" Value="member this.Topic : string" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Topic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.topic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="279d9-118">イベント サブスクリプションのトピックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="279d9-118">Gets name of the topic of the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>