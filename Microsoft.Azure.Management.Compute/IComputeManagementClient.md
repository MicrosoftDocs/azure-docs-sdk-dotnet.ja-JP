<Type Name="IComputeManagementClient" FullName="Microsoft.Azure.Management.Compute.IComputeManagementClient">
  <TypeSignature Language="C#" Value="public interface IComputeManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IComputeManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IComputeManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3e373-101">クライアントを計算します。</span><span class="sxs-lookup"><span data-stu-id="3e373-101">Compute Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e373-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations AvailabilitySets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations AvailabilitySets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.AvailabilitySets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySets As IAvailabilitySetsOperations" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySets : Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.AvailabilitySets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IAvailabilitySetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-103">IAvailabilitySetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-103">Gets the IAvailabilitySetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-104">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="3e373-104">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IContainerServicesOperations ContainerServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IContainerServicesOperations ContainerServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.ContainerServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerServices As IContainerServicesOperations" />
      <MemberSignature Language="F#" Value="member this.ContainerServices : Microsoft.Azure.Management.Compute.IContainerServicesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.ContainerServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IContainerServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-105">IContainerServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-105">Gets the IContainerServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="3e373-106">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-107">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e373-107">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IDisksOperations Disks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IDisksOperations Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.Disks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Disks As IDisksOperations" />
      <MemberSignature Language="F#" Value="member this.Disks : Microsoft.Azure.Management.Compute.IDisksOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IDisksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-108">IDisksOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-108">Gets the IDisksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-109">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3e373-109">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="3e373-110">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="3e373-110">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IImagesOperations Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IImagesOperations Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As IImagesOperations" />
      <MemberSignature Language="F#" Value="member this.Images : Microsoft.Azure.Management.Compute.IImagesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-111">IImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-111">Gets the IImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-112">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="3e373-112">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="3e373-113">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="3e373-113">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IResourceSkusOperations ResourceSkus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IResourceSkusOperations ResourceSkus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.ResourceSkus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceSkus As IResourceSkusOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceSkus : Microsoft.Azure.Management.Compute.IResourceSkusOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.ResourceSkus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IResourceSkusOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-114">IResourceSkusOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-114">Gets the IResourceSkusOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-115">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="3e373-115">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshots">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.ISnapshotsOperations Snapshots { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.ISnapshotsOperations Snapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.Snapshots" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Snapshots As ISnapshotsOperations" />
      <MemberSignature Language="F#" Value="member this.Snapshots : Microsoft.Azure.Management.Compute.ISnapshotsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.Snapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.ISnapshotsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-116">ISnapshotsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-116">Gets the ISnapshotsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-117">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報。</span><span class="sxs-lookup"><span data-stu-id="3e373-117">Subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="3e373-118">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="3e373-118">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IUsageOperations Usage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IUsageOperations Usage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.Usage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usage As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usage : Microsoft.Azure.Management.Compute.IUsageOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.Usage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-119">IUsageOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-119">Gets the IUsageOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensionImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensionImages As IVirtualMachineExtensionImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensionImages : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-120">IVirtualMachineExtensionImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-120">Gets the IVirtualMachineExtensionImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations VirtualMachineExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations VirtualMachineExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensions As IVirtualMachineExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensions : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-121">IVirtualMachineExtensionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-121">Gets the IVirtualMachineExtensionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations VirtualMachineImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations VirtualMachineImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImages As IVirtualMachineImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImages : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-122">IVirtualMachineImagesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-122">Gets the IVirtualMachineImagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineRunCommands">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineRunCommands" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineRunCommands As IVirtualMachineRunCommandsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineRunCommands : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineRunCommands" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-123">IVirtualMachineRunCommandsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-123">Gets the IVirtualMachineRunCommandsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachinesOperations VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachinesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachinesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-124">IVirtualMachinesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-124">Gets the IVirtualMachinesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetExtensions As IVirtualMachineScaleSetExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetExtensions : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-125">IVirtualMachineScaleSetExtensionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-125">Gets the IVirtualMachineScaleSetExtensionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetRollingUpgrades">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations VirtualMachineScaleSetRollingUpgrades { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations VirtualMachineScaleSetRollingUpgrades" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetRollingUpgrades" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetRollingUpgrades As IVirtualMachineScaleSetRollingUpgradesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetRollingUpgrades : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetRollingUpgrades" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetRollingUpgradesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-126">IVirtualMachineScaleSetRollingUpgradesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-126">Gets the IVirtualMachineScaleSetRollingUpgradesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSets As IVirtualMachineScaleSetsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSets : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-127">IVirtualMachineScaleSetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-127">Gets the IVirtualMachineScaleSetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetVMs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetVMs As IVirtualMachineScaleSetVMsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetVMs : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-128">IVirtualMachineScaleSetVMsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-128">Gets the IVirtualMachineScaleSetVMsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSizes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations VirtualMachineSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations VirtualMachineSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSizes As IVirtualMachineSizesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSizes : Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations" Usage="Microsoft.Azure.Management.Compute.IComputeManagementClient.VirtualMachineSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e373-129">IVirtualMachineSizesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e373-129">Gets the IVirtualMachineSizesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>