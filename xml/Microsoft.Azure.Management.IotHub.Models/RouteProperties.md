<Type Name="RouteProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RouteProperties">
  <TypeSignature Language="C#" Value="public class RouteProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RouteProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteProperties" />
  <TypeSignature Language="F#" Value="type RouteProperties = class" />
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
            <span data-ttu-id="dafd5-101">IoT ハブを使用してエンドポイントにメッセージをルーティングするルーティング規則のプロパティ。</span><span class="sxs-lookup"><span data-stu-id="dafd5-101">The properties of a routing rule that your IoT hub uses to route messages to endpoints.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dafd5-102">RouteProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-102">Initializes a new instance of the RouteProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteProperties (string name, string source, System.Collections.Generic.IList&lt;string&gt; endpointNames, bool isEnabled, string condition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string source, class System.Collections.Generic.IList`1&lt;string&gt; endpointNames, bool isEnabled, string condition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, source As String, endpointNames As IList(Of String), isEnabled As Boolean, Optional condition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RouteProperties : string * string * System.Collections.Generic.IList&lt;string&gt; * bool * string -&gt; Microsoft.Azure.Management.IotHub.Models.RouteProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RouteProperties (name, source, endpointNames, isEnabled, condition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="endpointNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dafd5-103">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="dafd5-103">The name of the route.</span></span> <span data-ttu-id="dafd5-104">名前は、英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができます、64 文字の最大長であるおよび一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="dafd5-104">The name can only include alphanumeric characters, periods, underscores, hyphens, has a maximum length of 64 characters, and must be unique.</span></span></param>
        <param name="source"><span data-ttu-id="dafd5-105">DeviceMessages などに、適用されるルーティング ルールがあるソース。</span><span class="sxs-lookup"><span data-stu-id="dafd5-105">The source that the routing rule is to be applied to, such as DeviceMessages.</span></span> <span data-ttu-id="dafd5-106">使用可能な値が含まれます: 'DeviceMessages'、'TwinChangeEvents'、'DeviceLifecycleEvents'、'DeviceJobLifecycleEvents'</span><span class="sxs-lookup"><span data-stu-id="dafd5-106">Possible values include: 'DeviceMessages', 'TwinChangeEvents', 'DeviceLifecycleEvents', 'DeviceJobLifecycleEvents'</span></span></param>
        <param name="endpointNames"><span data-ttu-id="dafd5-107">条件を満たすメッセージのルーティング先エンドポイントのリスト。</span><span class="sxs-lookup"><span data-stu-id="dafd5-107">The list of endpoints to which messages that satisfy the condition are routed.</span></span> <span data-ttu-id="dafd5-108">現在 1 つのみのエンドポイントは許可されています。</span><span class="sxs-lookup"><span data-stu-id="dafd5-108">Currently only one endpoint is allowed.</span></span></param>
        <param name="isEnabled"><span data-ttu-id="dafd5-109">ルートが有効になっているかどうかを指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-109">Used to specify whether a route is enabled.</span></span></param>
        <param name="condition"><span data-ttu-id="dafd5-110">ルーティング規則を適用する評価する条件。</span><span class="sxs-lookup"><span data-stu-id="dafd5-110">The condition that is evaluated to apply the routing rule.</span></span> <span data-ttu-id="dafd5-111">条件を指定しない場合、既定で true と評価します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-111">If no condition is provided, it evaluates to true by default.</span></span> <span data-ttu-id="dafd5-112">文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span><span class="sxs-lookup"><span data-stu-id="dafd5-112">For grammar, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span></span></param>
        <summary>
            <span data-ttu-id="dafd5-113">RouteProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-113">Initializes a new instance of the RouteProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public string Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As String" />
      <MemberSignature Language="F#" Value="member this.Condition : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="condition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dafd5-114">取得またはルーティング規則を適用する評価される条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-114">Gets or sets the condition that is evaluated to apply the routing rule.</span></span> <span data-ttu-id="dafd5-115">条件を指定しない場合、既定で true と評価します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-115">If no condition is provided, it evaluates to true by default.</span></span>
            <span data-ttu-id="dafd5-116">文法を参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span><span class="sxs-lookup"><span data-stu-id="dafd5-116">For grammar, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EndpointNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EndpointNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.EndpointNames" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EndpointNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.EndpointNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dafd5-117">取得または条件を満たすメッセージのルーティング先エンドポイントのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-117">Gets or sets the list of endpoints to which messages that satisfy the condition are routed.</span></span> <span data-ttu-id="dafd5-118">現在 1 つのみのエンドポイントは許可されています。</span><span class="sxs-lookup"><span data-stu-id="dafd5-118">Currently only one endpoint is allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dafd5-119">取得または設定のルートが有効になっているかどうかを指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-119">Gets or sets used to specify whether a route is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Name" />
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
            <span data-ttu-id="dafd5-120">取得またはルートの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-120">Gets or sets the name of the route.</span></span> <span data-ttu-id="dafd5-121">名前は、英数字、ピリオド、アンダー スコア、ハイフンのみを含めることができます、64 文字の最大長であるおよび一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="dafd5-121">The name can only include alphanumeric characters, periods, underscores, hyphens, has a maximum length of 64 characters, and must be unique.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RouteProperties.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dafd5-122">取得または DeviceMessages などに、適用されるルーティング ルールがあるソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-122">Gets or sets the source that the routing rule is to be applied to, such as DeviceMessages.</span></span> <span data-ttu-id="dafd5-123">使用可能な値が含まれます: 'DeviceMessages'、'TwinChangeEvents'、'DeviceLifecycleEvents'、'DeviceJobLifecycleEvents'</span><span class="sxs-lookup"><span data-stu-id="dafd5-123">Possible values include: 'DeviceMessages', 'TwinChangeEvents', 'DeviceLifecycleEvents', 'DeviceJobLifecycleEvents'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RouteProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routeProperties.Validate " />
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
            <span data-ttu-id="dafd5-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="dafd5-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dafd5-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafd5-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>