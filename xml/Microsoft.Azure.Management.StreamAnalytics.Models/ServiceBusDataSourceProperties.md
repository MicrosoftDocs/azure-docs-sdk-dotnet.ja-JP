<Type Name="ServiceBusDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties">
  <TypeSignature Language="C#" Value="public class ServiceBusDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusDataSourceProperties" />
  <TypeSignature Language="F#" Value="type ServiceBusDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="89f89-101">Service Bus のデータ ソース (キュー、トピック、Event Hubs など) に関連付けられている一般的なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="89f89-101">The common properties that are associated with Service Bus data sources (Queues, Topics, Event Hubs, etc.).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89f89-102">ServiceBusDataSourceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89f89-102">Initializes a new instance of the ServiceBusDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusDataSourceProperties (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties : string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace"><span data-ttu-id="89f89-103">目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-103">The namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyName"><span data-ttu-id="89f89-104">イベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシーの名前。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-104">The shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyKey"><span data-ttu-id="89f89-105">指定した共有アクセス ポリシーの共有アクセス ポリシー キー。</span><span class="sxs-lookup"><span data-stu-id="89f89-105">The shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="89f89-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="89f89-107">ServiceBusDataSourceProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="89f89-107">Initializes a new instance of the ServiceBusDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceBusNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89f89-108">取得または目的のイベント ハブ、Service Bus のキュー、Service Bus トピックなどに関連付けられている名前空間を設定します。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-108">Gets or sets the namespace that is associated with the desired Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.SharedAccessPolicyKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sharedAccessPolicyKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89f89-109">取得または指定した共有アクセス ポリシーの共有アクセス ポリシーのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="89f89-109">Gets or sets the shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="89f89-110">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-110">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyName">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusDataSourceProperties.SharedAccessPolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sharedAccessPolicyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89f89-111">取得またはイベント ハブ、Service Bus キュー、Service Bus トピックなどの共有アクセス ポリシー名を設定します。PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="89f89-111">Gets or sets the shared access policy name for the Event Hub, Service Bus Queue, Service Bus Topic, etc. Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>