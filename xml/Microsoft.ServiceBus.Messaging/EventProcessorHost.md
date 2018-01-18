<Type Name="EventProcessorHost" FullName="Microsoft.ServiceBus.Messaging.EventProcessorHost">
  <TypeSignature Language="C#" Value="public class EventProcessorHost : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventProcessorHost extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />
  <TypeSignature Language="VB.NET" Value="Public Class EventProcessorHost&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventProcessorHost = class&#xA;    interface IPartitionObserver&lt;BlobLease&gt;&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="9f409-101">Event Hubs のイベント データを処理するためには、ホストを表します。</span><span class="sxs-lookup"><span data-stu-id="9f409-101">Represents a host for processing Event Hubs event data.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubConnectionString">To be added.</param>
        <param name="storageConnectionString">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.EventProcessorOptions, class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, class System.Func`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.Func{Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory},System.Func{Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubClientFactory As Func(Of EventProcessorOptions, MessagingFactory), storageClientFactory As Func(Of CloudBlobClient))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions, Microsoft.ServiceBus.Messaging.MessagingFactory&gt; * Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubClientFactory, storageClientFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubClientFactory" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" />
        <Parameter Name="storageClientFactory" Type="System.Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt;" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubClientFactory">To be added.</param>
        <param name="storageClientFactory">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="9f409-102">名前、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="9f409-102">The name of the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance.</span></span> <span data-ttu-id="9f409-103">この名前は、ホストの各インスタンスに対して一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f409-103">This name must be unique for each instance of the host.</span></span></param>
        <param name="eventHubPath"><span data-ttu-id="9f409-104">イベント データの受信を開始する、Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="9f409-104">The path to the Event Hub from which to start receiving event data.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="9f409-105">イベント データの受信を開始するイベント ハブ コンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9f409-105">The name of the Event Hubs consumer group from which to start receiving event data.</span></span></param>
        <param name="eventHubConnectionString"><span data-ttu-id="9f409-106">イベント ハブの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="9f409-106">The connection string for the Event Hub.</span></span></param>
        <param name="storageConnectionString"><span data-ttu-id="9f409-107">パーティションの配布を使用する Azure Blob ストレージ アカウントの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="9f409-107">The connection string for the Azure Blob storage account to use for partition distribution.</span></span></param>
        <summary><span data-ttu-id="9f409-108"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9f409-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory, string leaseContainerName, string leaseBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.EventProcessorOptions, class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; eventHubClientFactory, class System.Func`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; storageClientFactory, string leaseContainerName, string leaseBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.Func{Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory},System.Func{Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubClientFactory As Func(Of EventProcessorOptions, MessagingFactory), storageClientFactory As Func(Of CloudBlobClient), leaseContainerName As String, Optional leaseBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions, Microsoft.ServiceBus.Messaging.MessagingFactory&gt; * Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt; * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubClientFactory, storageClientFactory, leaseContainerName, leaseBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubClientFactory" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.EventProcessorOptions,Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" />
        <Parameter Name="storageClientFactory" Type="System.Func&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient&gt;" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="leaseBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubClientFactory">To be added.</param>
        <param name="storageClientFactory">To be added.</param>
        <param name="leaseContainerName">To be added.</param>
        <param name="leaseBlobPrefix">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string leaseBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string leaseBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String, Optional leaseBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventProcessorHost : string * string * string * string * string * string * string -&gt; Microsoft.ServiceBus.Messaging.EventProcessorHost" Usage="new Microsoft.ServiceBus.Messaging.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName, leaseBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="leaseBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">To be added.</param>
        <param name="eventHubPath">To be added.</param>
        <param name="consumerGroupName">To be added.</param>
        <param name="eventHubConnectionString">To be added.</param>
        <param name="storageConnectionString">To be added.</param>
        <param name="leaseContainerName">To be added.</param>
        <param name="leaseBlobPrefix">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventProcessorHost.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="eventProcessorHost.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.ServiceBus.Messaging.EventProcessorHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="9f409-109">これは一意なホスト名を取得の名前、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="9f409-109">Gets the host name, which is a unique name for the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance.</span></span></summary>
        <value><span data-ttu-id="9f409-110">ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="9f409-110">The host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionManagerOptions">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionManagerOptions PartitionManagerOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.PartitionManagerOptions PartitionManagerOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionManagerOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.PartitionManagerOptions : Microsoft.ServiceBus.Messaging.PartitionManagerOptions with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorHost.PartitionManagerOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="9f409-111">取得または設定、<see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" />インスタンスによって使用される、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9f409-111">Gets or sets the <see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" /> instance used by the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> object.</span></span></summary>
        <value><span data-ttu-id="9f409-112"><see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" /> インスタンス。</span><span class="sxs-lookup"><span data-stu-id="9f409-112">The <see cref="T:Microsoft.ServiceBus.Messaging.PartitionManagerOptions" /> instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; () where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As IEventProcessor) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventProcessorHost.RegisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="9f409-113">アプリケーション固有の実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="9f409-113">Implementation of your application-specific <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <summary><span data-ttu-id="9f409-114">非同期的を登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />インターフェイスの実装を使用するホストと、<see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" />ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="9f409-114">Asynchronously registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> interface implementation with the host using the <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> factory.</span></span> <span data-ttu-id="9f409-115">また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="9f409-115">This method also starts the host and enables it to start participating in the partition distribution process.</span></span></summary>
        <returns><span data-ttu-id="9f409-116">タスクを示す、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンスが開始します。</span><span class="sxs-lookup"><span data-stu-id="9f409-116">A task indicating that the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance has started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorAsync``1(Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As IEventProcessor) (processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventProcessorHost.RegisterEventProcessorAsync processorOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="9f409-117">アプリケーション固有の実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="9f409-117">Implementation of your application-specific <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="processorOptions"><span data-ttu-id="9f409-118"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />イベント ポンプのさまざまな側面を制御するオブジェクトを作成、特定の Event Hubs のパーティションの所有権が取得されるときにします。</span><span class="sxs-lookup"><span data-stu-id="9f409-118">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object that controls various aspects of the event pump created when ownership is acquired for a given Event Hubs partition.</span></span></param>
        <summary><span data-ttu-id="9f409-119">非同期的を登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />インターフェイスの実装を使用するホストと、<see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" />ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="9f409-119">Asynchronously registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> interface implementation with the host using the <see cref="T:Microsoft.ServiceBus.Messaging.DefaultEventProcessorFactory`1" /> factory.</span></span> <span data-ttu-id="9f409-120">また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。</span><span class="sxs-lookup"><span data-stu-id="9f409-120">This method also starts the host and enables it to start participating in the partition distribution process.</span></span></summary>
        <returns><span data-ttu-id="9f409-121">タスクを示す、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンスが開始します。</span><span class="sxs-lookup"><span data-stu-id="9f409-121">A task indicating that the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance has started.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="9f409-122">登録するファクトリ。</span><span class="sxs-lookup"><span data-stu-id="9f409-122">The factory to register.</span></span></param>
        <summary><span data-ttu-id="9f409-123">非同期的に、イベント プロセッサ ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="9f409-123">Asynchronously registers the event processor factory.</span></span></summary>
        <returns><span data-ttu-id="9f409-124">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="9f409-124">The task representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.IEventProcessorFactory factory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory, processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync (factory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="9f409-125">登録するファクトリ。</span><span class="sxs-lookup"><span data-stu-id="9f409-125">The factory to register.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="9f409-126"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />イベント ポンプのさまざまな側面を制御するオブジェクトを作成、特定の Event Hubs のパーティションの所有権が取得されるときにします。</span><span class="sxs-lookup"><span data-stu-id="9f409-126">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object that controls various aspects of the event pump created when ownership is acquired for a given Event Hubs partition.</span></span></param>
        <summary><span data-ttu-id="9f409-127">非同期的に、イベント プロセッサ ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="9f409-127">Asynchronously registers the event processor factory.</span></span></summary>
        <returns><span data-ttu-id="9f409-128"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="9f409-128">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllConnections">
      <MemberSignature Language="C#" Value="public void ResetAllConnections ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetAllConnections() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.ResetAllConnections" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetAllConnections ()" />
      <MemberSignature Language="F#" Value="member this.ResetAllConnections : unit -&gt; unit" Usage="eventProcessorHost.ResetAllConnections " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public void ResetConnection (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetConnection(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.ResetConnection(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetConnection (partitionId As String)" />
      <MemberSignature Language="F#" Value="member this.ResetConnection : string -&gt; unit" Usage="eventProcessorHost.ResetConnection partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterEventProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterEventProcessorAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterEventProcessorAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorHost.UnregisterEventProcessorAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterEventProcessorAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.UnregisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus.Messaging.EventProcessorHost</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.Messaging.EventProcessorHost/&lt;UnregisterEventProcessorAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="9f409-129">非同期的にシャット ダウン、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="9f409-129">Asynchronously shuts down the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance.</span></span> <span data-ttu-id="9f409-130">このメソッドは現在保持されているすべてのパーティションでリースを保持し、により、各<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />インスタンスが正常にシャット ダウンを呼び出すことによって、<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />メソッドを<see cref="F:Microsoft.ServiceBus.Messaging.CloseReason.Shutdown" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9f409-130">This method maintains the leases on all partitions currently held, and enables each <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> instance to shut down cleanly by invoking the <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> method with a <see cref="F:Microsoft.ServiceBus.Messaging.CloseReason.Shutdown" /> object.</span></span></summary>
        <returns><span data-ttu-id="9f409-131">タスクを示す、<see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" />インスタンスが停止しました。</span><span class="sxs-lookup"><span data-stu-id="9f409-131">A task that indicates the <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorHost" /> instance has stopped.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>