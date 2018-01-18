<Type Name="IntegrationRuntimeNodeMonitoringData" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeNodeMonitoringData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeNodeMonitoringData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeNodeMonitoringData" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeNodeMonitoringData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="34e61-101">統合ランタイム ノード用のデータを監視します。</span><span class="sxs-lookup"><span data-stu-id="34e61-101">Monitoring data for integration runtime node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeNodeMonitoringData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="34e61-102">IntegrationRuntimeNodeMonitoringData クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34e61-102">Initializes a new instance of the IntegrationRuntimeNodeMonitoringData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeNodeMonitoringData (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string nodeName = null, Nullable&lt;int&gt; availableMemoryInMB = null, Nullable&lt;double&gt; cpuUtilization = null, Nullable&lt;int&gt; concurrentJobsLimit = null, Nullable&lt;int&gt; concurrentJobsRunning = null, Nullable&lt;int&gt; maxConcurrentJobs = null, Nullable&lt;double&gt; sentBytes = null, Nullable&lt;double&gt; receivedBytes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string nodeName, valuetype System.Nullable`1&lt;int32&gt; availableMemoryInMB, valuetype System.Nullable`1&lt;float64&gt; cpuUtilization, valuetype System.Nullable`1&lt;int32&gt; concurrentJobsLimit, valuetype System.Nullable`1&lt;int32&gt; concurrentJobsRunning, valuetype System.Nullable`1&lt;int32&gt; maxConcurrentJobs, valuetype System.Nullable`1&lt;float64&gt; sentBytes, valuetype System.Nullable`1&lt;float64&gt; receivedBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional nodeName As String = null, Optional availableMemoryInMB As Nullable(Of Integer) = null, Optional cpuUtilization As Nullable(Of Double) = null, Optional concurrentJobsLimit As Nullable(Of Integer) = null, Optional concurrentJobsRunning As Nullable(Of Integer) = null, Optional maxConcurrentJobs As Nullable(Of Integer) = null, Optional sentBytes As Nullable(Of Double) = null, Optional receivedBytes As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData (additionalProperties, nodeName, availableMemoryInMB, cpuUtilization, concurrentJobsLimit, concurrentJobsRunning, maxConcurrentJobs, sentBytes, receivedBytes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="availableMemoryInMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cpuUtilization" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="concurrentJobsLimit" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="concurrentJobsRunning" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxConcurrentJobs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sentBytes" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="receivedBytes" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="34e61-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="34e61-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="nodeName"><span data-ttu-id="34e61-104">統合ランタイム ノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="34e61-104">Name of the integration runtime node.</span></span></param>
        <param name="availableMemoryInMB"><span data-ttu-id="34e61-105">統合ランタイム ノードで使用可能なメモリ (MB)。</span><span class="sxs-lookup"><span data-stu-id="34e61-105">Available memory (MB) on the integration runtime node.</span></span></param>
        <param name="cpuUtilization"><span data-ttu-id="34e61-106">統合ランタイム ノードに CPU の割合。</span><span class="sxs-lookup"><span data-stu-id="34e61-106">CPU percentage on the integration runtime node.</span></span></param>
        <param name="concurrentJobsLimit"><span data-ttu-id="34e61-107">統合ランタイム ノードで最大の同時実行ジョブです。</span><span class="sxs-lookup"><span data-stu-id="34e61-107">Maximum concurrent jobs on the integration runtime node.</span></span></param>
        <param name="concurrentJobsRunning"><span data-ttu-id="34e61-108">統合ランタイム ノードで実行中のジョブの数。</span><span class="sxs-lookup"><span data-stu-id="34e61-108">The number of jobs currently running on the integration runtime node.</span></span></param>
        <param name="maxConcurrentJobs"><span data-ttu-id="34e61-109">この統合ランタイムで最大の同時実行ジョブです。</span><span class="sxs-lookup"><span data-stu-id="34e61-109">The maximum concurrent jobs in this integration runtime.</span></span></param>
        <param name="sentBytes"><span data-ttu-id="34e61-110">統合ランタイム ノードに送信されたバイト。</span><span class="sxs-lookup"><span data-stu-id="34e61-110">Sent bytes on the integration runtime node.</span></span></param>
        <param name="receivedBytes"><span data-ttu-id="34e61-111">統合ランタイム ノードで受信したバイト数。</span><span class="sxs-lookup"><span data-stu-id="34e61-111">Received bytes on the integration runtime node.</span></span></param>
        <summary>
            <span data-ttu-id="34e61-112">IntegrationRuntimeNodeMonitoringData クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="34e61-112">Initializes a new instance of the IntegrationRuntimeNodeMonitoringData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-113">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="34e61-113">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableMemoryInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AvailableMemoryInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AvailableMemoryInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.AvailableMemoryInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailableMemoryInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AvailableMemoryInMB : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.AvailableMemoryInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableMemoryInMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-114">統合ランタイム ノードで使用可能なメモリ (MB) を取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-114">Gets available memory (MB) on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentJobsLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ConcurrentJobsLimit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ConcurrentJobsLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ConcurrentJobsLimit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentJobsLimit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ConcurrentJobsLimit : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ConcurrentJobsLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="concurrentJobsLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-115">統合ランタイム ノードの最大の同時実行ジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-115">Gets maximum concurrent jobs on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentJobsRunning">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ConcurrentJobsRunning { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ConcurrentJobsRunning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ConcurrentJobsRunning" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConcurrentJobsRunning As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ConcurrentJobsRunning : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ConcurrentJobsRunning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="concurrentJobsRunning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-116">統合ランタイム ノードで現在実行中のジョブの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-116">Gets the number of jobs currently running on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CpuUtilization">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CpuUtilization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CpuUtilization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.CpuUtilization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CpuUtilization As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CpuUtilization : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.CpuUtilization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cpuUtilization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-117">統合ランタイム ノードの CPU の割合を取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-117">Gets CPU percentage on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentJobs">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxConcurrentJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxConcurrentJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.MaxConcurrentJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxConcurrentJobs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentJobs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.MaxConcurrentJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxConcurrentJobs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-118">この統合ランタイムでは、最大の同時実行ジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-118">Gets the maximum concurrent jobs in this integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-119">統合ランタイム ノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="34e61-119">Gets name of the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceivedBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ReceivedBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ReceivedBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ReceivedBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceivedBytes As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ReceivedBytes : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.ReceivedBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="receivedBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-120">統合ランタイム ノードで受信したバイト数を取得。</span><span class="sxs-lookup"><span data-stu-id="34e61-120">Gets received bytes on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SentBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; SentBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; SentBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.SentBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SentBytes As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.SentBytes : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeMonitoringData.SentBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sentBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34e61-121">バイトを統合ランタイム ノードに送信されます。</span><span class="sxs-lookup"><span data-stu-id="34e61-121">Gets sent bytes on the integration runtime node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>