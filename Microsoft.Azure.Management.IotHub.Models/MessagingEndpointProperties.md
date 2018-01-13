<Type Name="MessagingEndpointProperties" FullName="Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties">
  <TypeSignature Language="C#" Value="public class MessagingEndpointProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessagingEndpointProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingEndpointProperties" />
  <TypeSignature Language="F#" Value="type MessagingEndpointProperties = class" />
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
            <span data-ttu-id="f1a62-101">この IoT ハブによって使用されるメッセージング エンドポイントのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f1a62-101">The properties of the messaging endpoints used by this IoT hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEndpointProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f1a62-102">MessagingEndpointProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-102">Initializes a new instance of the MessagingEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingEndpointProperties (Nullable&lt;TimeSpan&gt; lockDurationAsIso8601 = null, Nullable&lt;TimeSpan&gt; ttlAsIso8601 = null, Nullable&lt;int&gt; maxDeliveryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDurationAsIso8601, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ttlAsIso8601, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lockDurationAsIso8601 As Nullable(Of TimeSpan) = null, Optional ttlAsIso8601 As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties (lockDurationAsIso8601, ttlAsIso8601, maxDeliveryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lockDurationAsIso8601" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="ttlAsIso8601" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="lockDurationAsIso8601"><span data-ttu-id="f1a62-103">ロックの期間です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-103">The lock duration.</span></span> <span data-ttu-id="f1a62-104">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-104">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span></param>
        <param name="ttlAsIso8601"><span data-ttu-id="f1a62-105">メッセージの IoT hub によって期限切れとなる前に使用する利用可能な期間。</span><span class="sxs-lookup"><span data-stu-id="f1a62-105">The period of time for which a message is available to consume before it is expired by the IoT hub.</span></span> <span data-ttu-id="f1a62-106">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-106">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span></param>
        <param name="maxDeliveryCount"><span data-ttu-id="f1a62-107">IoT hub がメッセージを配信する試行回数。</span><span class="sxs-lookup"><span data-stu-id="f1a62-107">The number of times the IoT hub attempts to deliver a message.</span></span> <span data-ttu-id="f1a62-108">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-108">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span></param>
        <summary>
            <span data-ttu-id="f1a62-109">MessagingEndpointProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-109">Initializes a new instance of the MessagingEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDurationAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDurationAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDurationAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.LockDurationAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDurationAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDurationAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.LockDurationAsIso8601" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lockDurationAsIso8601")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1a62-110">取得またはロック期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-110">Gets or sets the lock duration.</span></span> <span data-ttu-id="f1a62-111">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-111">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1a62-112">取得または IoT ハブがメッセージを配信する試行回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-112">Gets or sets the number of times the IoT hub attempts to deliver a message.</span></span> <span data-ttu-id="f1a62-113">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-113">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TtlAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TtlAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TtlAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.TtlAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property TtlAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TtlAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.TtlAsIso8601" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ttlAsIso8601")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1a62-114">取得またはメッセージの IoT hub によって期限切れとなる前に使用する利用可能な期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-114">Gets or sets the period of time for which a message is available to consume before it is expired by the IoT hub.</span></span> <span data-ttu-id="f1a62-115">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload です。</span><span class="sxs-lookup"><span data-stu-id="f1a62-115">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="messagingEndpointProperties.Validate " />
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
            <span data-ttu-id="f1a62-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f1a62-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1a62-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1a62-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>