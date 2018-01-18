<Type Name="FeedbackProperties" FullName="Microsoft.Azure.Management.IotHub.Models.FeedbackProperties">
  <TypeSignature Language="C#" Value="public class FeedbackProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FeedbackProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FeedbackProperties" />
  <TypeSignature Language="F#" Value="type FeedbackProperties = class" />
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
            <span data-ttu-id="7f218-101">フィードバック メッセージ キューをクラウドからデバイスのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7f218-101">The properties of the feedback queue for cloud-to-device messages.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedbackProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f218-102">FeedbackProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f218-102">Initializes a new instance of the FeedbackProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedbackProperties (Nullable&lt;TimeSpan&gt; lockDurationAsIso8601 = null, Nullable&lt;TimeSpan&gt; ttlAsIso8601 = null, Nullable&lt;int&gt; maxDeliveryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDurationAsIso8601, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ttlAsIso8601, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lockDurationAsIso8601 As Nullable(Of TimeSpan) = null, Optional ttlAsIso8601 As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.FeedbackProperties : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.FeedbackProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.FeedbackProperties (lockDurationAsIso8601, ttlAsIso8601, maxDeliveryCount)" />
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
        <param name="lockDurationAsIso8601"><span data-ttu-id="7f218-103">フィードバック キューのロックの期間です。</span><span class="sxs-lookup"><span data-stu-id="7f218-103">The lock duration for the feedback queue.</span></span> <span data-ttu-id="7f218-104">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-104">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span></param>
        <param name="ttlAsIso8601"><span data-ttu-id="7f218-105">メッセージの IoT hub によって期限切れとなる前に使用する利用可能な期間。</span><span class="sxs-lookup"><span data-stu-id="7f218-105">The period of time for which a message is available to consume before it is expired by the IoT hub.</span></span> <span data-ttu-id="7f218-106">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-106">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span></param>
        <param name="maxDeliveryCount"><span data-ttu-id="7f218-107">IoT hub フィードバック キューにメッセージを配信しようとしました。 時間数。</span><span class="sxs-lookup"><span data-stu-id="7f218-107">The number of times the IoT hub attempts to deliver a message on the feedback queue.</span></span> <span data-ttu-id="7f218-108">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-108">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span></param>
        <summary>
            <span data-ttu-id="7f218-109">FeedbackProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f218-109">Initializes a new instance of the FeedbackProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDurationAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDurationAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDurationAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.LockDurationAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDurationAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDurationAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.LockDurationAsIso8601" />
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
            <span data-ttu-id="7f218-110">取得またはフィードバック キューのロック期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f218-110">Gets or sets the lock duration for the feedback queue.</span></span> <span data-ttu-id="7f218-111">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-111">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.MaxDeliveryCount" />
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
            <span data-ttu-id="7f218-112">取得または IoT ハブがフィードバック キューにメッセージを配信する試行回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f218-112">Gets or sets the number of times the IoT hub attempts to deliver a message on the feedback queue.</span></span> <span data-ttu-id="7f218-113">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-113">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TtlAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TtlAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TtlAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.TtlAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property TtlAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TtlAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.TtlAsIso8601" />
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
            <span data-ttu-id="7f218-114">取得またはメッセージの IoT hub によって期限切れとなる前に使用する利用可能な期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f218-114">Gets or sets the period of time for which a message is available to consume before it is expired by the IoT hub.</span></span> <span data-ttu-id="7f218-115">参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages です。</span><span class="sxs-lookup"><span data-stu-id="7f218-115">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FeedbackProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="feedbackProperties.Validate " />
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
            <span data-ttu-id="7f218-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7f218-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7f218-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7f218-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>