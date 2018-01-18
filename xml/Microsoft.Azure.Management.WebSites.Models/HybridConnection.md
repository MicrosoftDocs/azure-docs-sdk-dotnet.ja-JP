<Type Name="HybridConnection" FullName="Microsoft.Azure.Management.WebSites.Models.HybridConnection">
  <TypeSignature Language="C#" Value="public class HybridConnection : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnection extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HybridConnection" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnection&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HybridConnection = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2e146-101">ハイブリッド接続のコントラクト。</span><span class="sxs-lookup"><span data-stu-id="2e146-101">Hybrid Connection contract.</span></span> <span data-ttu-id="2e146-102">ハイブリッド接続の構成に使用されます。</span><span class="sxs-lookup"><span data-stu-id="2e146-102">This is used to configure a Hybrid Connection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e146-103">HybridConnection クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e146-103">Initializes a new instance of the HybridConnection class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnection (string id = null, string name = null, string kind = null, string type = null, string serviceBusNamespace = null, string relayName = null, string relayArmUri = null, string hostname = null, Nullable&lt;int&gt; port = null, string sendKeyName = null, string sendKeyValue = null, string serviceBusSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string serviceBusNamespace, string relayName, string relayArmUri, string hostname, valuetype System.Nullable`1&lt;int32&gt; port, string sendKeyName, string sendKeyValue, string serviceBusSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HybridConnection.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional serviceBusNamespace As String = null, Optional relayName As String = null, Optional relayArmUri As String = null, Optional hostname As String = null, Optional port As Nullable(Of Integer) = null, Optional sendKeyName As String = null, Optional sendKeyValue As String = null, Optional serviceBusSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HybridConnection : string * string * string * string * string * string * string * string * Nullable&lt;int&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnection" Usage="new Microsoft.Azure.Management.WebSites.Models.HybridConnection (id, name, kind, type, serviceBusNamespace, relayName, relayArmUri, hostname, port, sendKeyName, sendKeyValue, serviceBusSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="relayArmUri" Type="System.String" />
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sendKeyName" Type="System.String" />
        <Parameter Name="sendKeyValue" Type="System.String" />
        <Parameter Name="serviceBusSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2e146-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="2e146-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="2e146-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="2e146-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="2e146-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2e146-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="2e146-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2e146-107">Resource type.</span></span></param>
        <param name="serviceBusNamespace"><span data-ttu-id="2e146-108">Service Bus 名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="2e146-108">The name of the Service Bus namespace.</span></span></param>
        <param name="relayName"><span data-ttu-id="2e146-109">Service Bus リレーの名前。</span><span class="sxs-lookup"><span data-stu-id="2e146-109">The name of the Service Bus relay.</span></span></param>
        <param name="relayArmUri"><span data-ttu-id="2e146-110">Service Bus リレーを ARM URI。</span><span class="sxs-lookup"><span data-stu-id="2e146-110">The ARM URI to the Service Bus relay.</span></span></param>
        <param name="hostname"><span data-ttu-id="2e146-111">エンドポイントのホスト名です。</span><span class="sxs-lookup"><span data-stu-id="2e146-111">The hostname of the endpoint.</span></span></param>
        <param name="port"><span data-ttu-id="2e146-112">エンドポイントのポートです。</span><span class="sxs-lookup"><span data-stu-id="2e146-112">The port of the endpoint.</span></span></param>
        <param name="sendKeyName"><span data-ttu-id="2e146-113">送信のアクセス許可を持つ Service Bus キーの名前。</span><span class="sxs-lookup"><span data-stu-id="2e146-113">The name of the Service Bus key which has Send permissions.</span></span> <span data-ttu-id="2e146-114">Service Bus への認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="2e146-114">This is used to authenticate to Service Bus.</span></span></param>
        <param name="sendKeyValue"><span data-ttu-id="2e146-115">Service Bus キーの値。</span><span class="sxs-lookup"><span data-stu-id="2e146-115">The value of the Service Bus key.</span></span> <span data-ttu-id="2e146-116">Service Bus への認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="2e146-116">This is used to authenticate to Service Bus.</span></span> <span data-ttu-id="2e146-117">このキーは通常どおり返されません。 ARM、POST/listKeys API を代わりに使用します。</span><span class="sxs-lookup"><span data-stu-id="2e146-117">In ARM this key will not be returned normally, use the POST /listKeys API instead.</span></span></param>
        <param name="serviceBusSuffix"><span data-ttu-id="2e146-118">Service bus エンドポイントのサフィックス。</span><span class="sxs-lookup"><span data-stu-id="2e146-118">The suffix for the service bus endpoint.</span></span> <span data-ttu-id="2e146-119">既定ではこの \*.servicebus.windows.net。</span><span class="sxs-lookup"><span data-stu-id="2e146-119">By default this is .servicebus.windows.net</span></span></param>
        <summary>
            <span data-ttu-id="2e146-120">HybridConnection クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e146-120">Initializes a new instance of the HybridConnection class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hostname">
      <MemberSignature Language="C#" Value="public string Hostname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Hostname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.Hostname" />
      <MemberSignature Language="VB.NET" Value="Public Property Hostname As String" />
      <MemberSignature Language="F#" Value="member this.Hostname : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.Hostname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-121">取得またはエンドポイントのホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-121">Gets or sets the hostname of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-122">取得またはエンドポイントのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-122">Gets or sets the port of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayArmUri">
      <MemberSignature Language="C#" Value="public string RelayArmUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelayArmUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayArmUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayArmUri As String" />
      <MemberSignature Language="F#" Value="member this.RelayArmUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayArmUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.relayArmUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-123">取得または Service Bus リレーを ARM URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-123">Gets or sets the ARM URI to the Service Bus relay.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayName">
      <MemberSignature Language="C#" Value="public string RelayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayName" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayName As String" />
      <MemberSignature Language="F#" Value="member this.RelayName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.RelayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.relayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-124">取得または Service Bus リレーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-124">Gets or sets the name of the Service Bus relay.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyName">
      <MemberSignature Language="C#" Value="public string SendKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SendKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-125">取得または送信のアクセス許可を持つ Service Bus キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-125">Gets or sets the name of the Service Bus key which has Send permissions.</span></span> <span data-ttu-id="2e146-126">Service Bus への認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="2e146-126">This is used to authenticate to Service Bus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendKeyValue">
      <MemberSignature Language="C#" Value="public string SendKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property SendKeyValue As String" />
      <MemberSignature Language="F#" Value="member this.SendKeyValue : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.SendKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sendKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-127">取得または Service Bus キーの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-127">Gets or sets the value of the Service Bus key.</span></span> <span data-ttu-id="2e146-128">Service Bus への認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="2e146-128">This is used to authenticate to Service Bus.</span></span> <span data-ttu-id="2e146-129">このキーは通常どおり返されません。 ARM、POST/listKeys API を代わりに使用します。</span><span class="sxs-lookup"><span data-stu-id="2e146-129">In ARM this key will not be returned normally, use the POST /listKeys API instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e146-130">取得または Service Bus 名前空間の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-130">Gets or sets the name of the Service Bus namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusSuffix">
      <MemberSignature Language="C#" Value="public string ServiceBusSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusSuffix As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusSuffix : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HybridConnection.ServiceBusSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e146-131">取得または service bus エンドポイントのサフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e146-131">Gets or sets the suffix for the service bus endpoint.</span></span> <span data-ttu-id="2e146-132">既定ではこの \*.servicebus.windows.net。</span><span class="sxs-lookup"><span data-stu-id="2e146-132">By default this is .servicebus.windows.net</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>