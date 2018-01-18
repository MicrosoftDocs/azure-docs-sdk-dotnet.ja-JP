<Type Name="EventHubDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties">
  <TypeSignature Language="C#" Value="public class EventHubDataSourceProperties : Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubDataSourceProperties extends Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubDataSourceProperties&#xA;Inherits ServiceBusDataSourceProperties" />
  <TypeSignature Language="F#" Value="type EventHubDataSourceProperties = class&#xA;    inherit ServiceBusDataSourceProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f314-101">イベント ハブのデータ ソースに関連付けられている一般的なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8f314-101">The common properties that are associated with Event Hub data sources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f314-102">EventHubDataSourceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f314-102">Initializes a new instance of the EventHubDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubDataSourceProperties (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string eventHubName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string eventHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional eventHubName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties : string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, eventHubName)" />
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
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace"><span data-ttu-id="8f314-103">目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="8f314-103">The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyName"><span data-ttu-id="8f314-104">イベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシーの名前。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="8f314-104">The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyKey"><span data-ttu-id="8f314-105">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。</span><span class="sxs-lookup"><span data-stu-id="8f314-105">The shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="8f314-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="8f314-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="eventHubName"><span data-ttu-id="8f314-107">イベント ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="8f314-107">The name of the Event Hub.</span></span> <span data-ttu-id="8f314-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="8f314-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="8f314-109">EventHubDataSourceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f314-109">Initializes a new instance of the EventHubDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.EventHubDataSourceProperties.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventHubName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f314-110">取得またはイベント ハブの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8f314-110">Gets or sets the name of the Event Hub.</span></span> <span data-ttu-id="8f314-111">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="8f314-111">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>