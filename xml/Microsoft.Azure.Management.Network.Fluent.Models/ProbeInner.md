<Type Name="ProbeInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner">
  <TypeSignature Language="C#" Value="public class ProbeInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProbeInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ProbeInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ProbeInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="732a5-101">ロード バランサー プローブです。</span><span class="sxs-lookup"><span data-stu-id="732a5-101">A load balancer probe.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="732a5-102">ProbeInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="732a5-102">Initializes a new instance of the ProbeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner (string protocol, int port, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules = null, Nullable&lt;int&gt; intervalInSeconds = null, Nullable&lt;int&gt; numberOfProbes = null, string requestPath = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 port, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules, valuetype System.Nullable`1&lt;int32&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int32&gt; numberOfProbes, string requestPath, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor(System.String,System.Int32,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, port As Integer, Optional id As String = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional intervalInSeconds As Nullable(Of Integer) = null, Optional numberOfProbes As Nullable(Of Integer) = null, Optional requestPath As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner : string * int * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner (protocol, port, id, loadBalancingRules, intervalInSeconds, numberOfProbes, requestPath, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfProbes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestPath" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="732a5-103">エンドポイントのプロトコルです。</span><span class="sxs-lookup"><span data-stu-id="732a5-103">The protocol of the end point.</span></span> <span data-ttu-id="732a5-104">使用可能な値が: 'Http' または 'Tcp' です。</span><span class="sxs-lookup"><span data-stu-id="732a5-104">Possible values are: 'Http' or 'Tcp'.</span></span> <span data-ttu-id="732a5-105">'Tcp' が指定されている場合は受信 ACK はプローブを成功させるために必要です。</span><span class="sxs-lookup"><span data-stu-id="732a5-105">If 'Tcp' is specified, a received ACK is required for the probe to be successful.</span></span> <span data-ttu-id="732a5-106">'Http' が指定されている場合から 200 OK の応答、プローブを成功させるために必要な URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-106">If 'Http' is specified, a 200 OK response from the specifies URI is required for the probe to be successful.</span></span> <span data-ttu-id="732a5-107">使用可能な値が含まれます 'Http'、'Tcp'。</span><span class="sxs-lookup"><span data-stu-id="732a5-107">Possible values include: 'Http', 'Tcp'</span></span></param>
        <param name="port"><span data-ttu-id="732a5-108">プローブ通信用ポート。</span><span class="sxs-lookup"><span data-stu-id="732a5-108">The port for communicating the probe.</span></span> <span data-ttu-id="732a5-109">指定できる値は 1 以上 65535 以下です。</span><span class="sxs-lookup"><span data-stu-id="732a5-109">Possible values range from 1 to 65535, inclusive.</span></span></param>
        <param name="id">To be added.</param>
        <param name="loadBalancingRules"><span data-ttu-id="732a5-110">このプローブを使用するロード バランサー ルール。</span><span class="sxs-lookup"><span data-stu-id="732a5-110">The load balancer rules that use this probe.</span></span></param>
        <param name="intervalInSeconds"><span data-ttu-id="732a5-111">どのぐらいの頻度でエンドポイントに正常性状態をプローブするかを表す間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="732a5-111">The interval, in seconds, for how frequently to probe the endpoint for health status.</span></span> <span data-ttu-id="732a5-112">この間隔は、割り当てられているタイムアウト期間 (秒) の 1/2 よりもわずかに短くするのが一般的です。そうすることで、2 回のプローブを完全に実施したうえで、インスタンスをローテーションから除外することができます。</span><span class="sxs-lookup"><span data-stu-id="732a5-112">Typically, the interval is slightly less than half the allocated timeout period (in seconds) which allows two full probes before taking the instance out of rotation.</span></span> <span data-ttu-id="732a5-113">既定値は 15、最小値は 5 です。</span><span class="sxs-lookup"><span data-stu-id="732a5-113">The default value is 15, the minimum value is 5.</span></span></param>
        <param name="numberOfProbes"><span data-ttu-id="732a5-114">数は、応答と、さらにトラフィックをエンドポイントに配信されることを停止する場合、where をプローブします。</span><span class="sxs-lookup"><span data-stu-id="732a5-114">The number of probes where if no response, will result in stopping further traffic from being delivered to the endpoint.</span></span> <span data-ttu-id="732a5-115">この値により、実行されるエンドポイントも早くまたは Azure で使用される通常の期間よりも低速のローテーションから除外します。</span><span class="sxs-lookup"><span data-stu-id="732a5-115">This values allows endpoints to be taken out of rotation faster or slower than the typical times used in Azure.</span></span></param>
        <param name="requestPath"><span data-ttu-id="732a5-116">VM の正常性状態を要求する目的で使用される URI。</span><span class="sxs-lookup"><span data-stu-id="732a5-116">The URI used for requesting health status from the VM.</span></span> <span data-ttu-id="732a5-117">プロトコルは http に設定されている場合、パスが必要です。</span><span class="sxs-lookup"><span data-stu-id="732a5-117">Path is required if a protocol is set to http.</span></span>
            <span data-ttu-id="732a5-118">それ以外の場合は、許可されません。</span><span class="sxs-lookup"><span data-stu-id="732a5-118">Otherwise, it is not allowed.</span></span> <span data-ttu-id="732a5-119">既定値はありません。</span><span class="sxs-lookup"><span data-stu-id="732a5-119">There is no default value.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="732a5-120">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="732a5-120">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="732a5-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="732a5-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="732a5-122">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="732a5-122">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="732a5-123">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="732a5-123">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="732a5-124">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="732a5-124">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="732a5-125">ProbeInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="732a5-125">Initializes a new instance of the ProbeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-126">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="732a5-126">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-127">取得または、エンドポイントに対する正常性状態をプローブする頻度を秒単位で間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-127">Gets or sets the interval, in seconds, for how frequently to probe the endpoint for health status.</span></span> <span data-ttu-id="732a5-128">この間隔は、割り当てられているタイムアウト期間 (秒) の 1/2 よりもわずかに短くするのが一般的です。そうすることで、2 回のプローブを完全に実施したうえで、インスタンスをローテーションから除外することができます。</span><span class="sxs-lookup"><span data-stu-id="732a5-128">Typically, the interval is slightly less than half the allocated timeout period (in seconds) which allows two full probes before taking the instance out of rotation.</span></span>
            <span data-ttu-id="732a5-129">既定値は 15、最小値は 5 です。</span><span class="sxs-lookup"><span data-stu-id="732a5-129">The default value is 15, the minimum value is 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-130">このプローブを使用するバランサー ルールの負荷を取得します。</span><span class="sxs-lookup"><span data-stu-id="732a5-130">Gets the load balancer rules that use this probe.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="732a5-131">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="732a5-131">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="732a5-132">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="732a5-132">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfProbes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfProbes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfProbes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfProbes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfProbes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-133">取得または設定の数が、エンドポイントに配信されてからのトラフィックを停止するは、応答がなかった場合、where をプローブします。</span><span class="sxs-lookup"><span data-stu-id="732a5-133">Gets or sets the number of probes where if no response, will result in stopping further traffic from being delivered to the endpoint.</span></span>
            <span data-ttu-id="732a5-134">この値により、実行されるエンドポイントも早くまたは Azure で使用される通常の期間よりも低速のローテーションから除外します。</span><span class="sxs-lookup"><span data-stu-id="732a5-134">This values allows endpoints to be taken out of rotation faster or slower than the typical times used in Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-135">取得またはプローブ通信用ポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-135">Gets or sets the port for communicating the probe.</span></span> <span data-ttu-id="732a5-136">指定できる値は 1 以上 65535 以下です。</span><span class="sxs-lookup"><span data-stu-id="732a5-136">Possible values range from 1 to 65535, inclusive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-137">取得またはエンドポイントのプロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-137">Gets or sets the protocol of the end point.</span></span> <span data-ttu-id="732a5-138">使用可能な値が: 'Http' または 'Tcp' です。</span><span class="sxs-lookup"><span data-stu-id="732a5-138">Possible values are: 'Http' or 'Tcp'.</span></span> <span data-ttu-id="732a5-139">'Tcp' が指定されている場合は受信 ACK はプローブを成功させるために必要です。</span><span class="sxs-lookup"><span data-stu-id="732a5-139">If 'Tcp' is specified, a received ACK is required for the probe to be successful.</span></span> <span data-ttu-id="732a5-140">'Http' が指定されている場合から 200 OK の応答、プローブを成功させるために必要な URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-140">If 'Http' is specified, a 200 OK response from the specifies URI is required for the probe to be successful.</span></span> <span data-ttu-id="732a5-141">使用可能な値が含まれます 'Http'、'Tcp'。</span><span class="sxs-lookup"><span data-stu-id="732a5-141">Possible values include: 'Http', 'Tcp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="732a5-142">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="732a5-142">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="732a5-143">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="732a5-143">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestPath">
      <MemberSignature Language="C#" Value="public string RequestPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestPath As String" />
      <MemberSignature Language="F#" Value="member this.RequestPath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="732a5-144">取得または VM から正常性状態を要求するために使用する URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="732a5-144">Gets or sets the URI used for requesting health status from the VM.</span></span>
            <span data-ttu-id="732a5-145">プロトコルは http に設定されている場合、パスが必要です。</span><span class="sxs-lookup"><span data-stu-id="732a5-145">Path is required if a protocol is set to http.</span></span> <span data-ttu-id="732a5-146">それ以外の場合は、許可されません。</span><span class="sxs-lookup"><span data-stu-id="732a5-146">Otherwise, it is not allowed.</span></span> <span data-ttu-id="732a5-147">既定値はありません。</span><span class="sxs-lookup"><span data-stu-id="732a5-147">There is no default value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="probeInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="732a5-148">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="732a5-148">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="732a5-149">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="732a5-149">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>