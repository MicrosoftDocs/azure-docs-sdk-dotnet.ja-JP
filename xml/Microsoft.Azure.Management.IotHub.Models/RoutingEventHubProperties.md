<Type Name="RoutingEventHubProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties">
  <TypeSignature Language="C#" Value="public class RoutingEventHubProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingEventHubProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingEventHubProperties" />
  <TypeSignature Language="F#" Value="type RoutingEventHubProperties = class" />
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
            <span data-ttu-id="7e815-101">イベント ハブのエンドポイントに関連するプロパティ。</span><span class="sxs-lookup"><span data-stu-id="7e815-101">The properties related to an event hub endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEventHubProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e815-102">RoutingEventHubProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e815-102">Initializes a new instance of the RoutingEventHubProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEventHubProperties (string connectionString, string name, string subscriptionId = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string name, string subscriptionId, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, name As String, Optional subscriptionId As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties : string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties (connectionString, name, subscriptionId, resourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="7e815-103">イベント ハブのエンドポイントの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="7e815-103">The connection string of the event hub endpoint.</span></span> </param>
        <param name="name"><span data-ttu-id="7e815-104">このエンドポイントを識別する名前。</span><span class="sxs-lookup"><span data-stu-id="7e815-104">The name that identifies this endpoint.</span></span> <span data-ttu-id="7e815-105">名前は文字の英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができ、64 文字の最大長であります。</span><span class="sxs-lookup"><span data-stu-id="7e815-105">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="7e815-106">次の名前は予約されています。 イベント、operationsMonitoringEvents、fileNotifications、$default です。</span><span class="sxs-lookup"><span data-stu-id="7e815-106">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="7e815-107">エンドポイント名は、エンドポイントの種類で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e815-107">Endpoint names must be unique across endpoint types.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="7e815-108">イベント ハブのエンドポイントのサブスクリプションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="7e815-108">The subscription identifier of the event hub endpoint.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="7e815-109">イベント ハブのエンドポイントのリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7e815-109">The name of the resource group of the event hub endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="7e815-110">RoutingEventHubProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7e815-110">Initializes a new instance of the RoutingEventHubProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e815-111">取得またはイベント ハブのエンドポイントの接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="7e815-111">Gets or sets the connection string of the event hub endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e815-112">取得または設定をこのエンドポイントを識別する名前。</span><span class="sxs-lookup"><span data-stu-id="7e815-112">Gets or sets the name that identifies this endpoint.</span></span> <span data-ttu-id="7e815-113">名前は文字の英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができ、64 文字の最大長であります。</span><span class="sxs-lookup"><span data-stu-id="7e815-113">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="7e815-114">次の名前は予約されています。 イベント、operationsMonitoringEvents、fileNotifications、$default です。</span><span class="sxs-lookup"><span data-stu-id="7e815-114">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="7e815-115">エンドポイント名は、エンドポイントの種類で一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e815-115">Endpoint names must be unique across endpoint types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e815-116">取得またはイベント ハブのエンドポイントのリソース グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7e815-116">Gets or sets the name of the resource group of the event hub endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e815-117">取得またはイベント ハブのエンドポイントのサブスクリプション識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="7e815-117">Gets or sets the subscription identifier of the event hub endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingEventHubProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7e815-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7e815-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7e815-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7e815-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>