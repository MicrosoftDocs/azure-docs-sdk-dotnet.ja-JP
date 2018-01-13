<Type Name="RegistryManager" FullName="Microsoft.Azure.Devices.RegistryManager">
  <TypeSignature Language="C#" Value="public abstract class RegistryManager : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RegistryManager extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.RegistryManager" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RegistryManager&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type RegistryManager = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <summary>
            <span data-ttu-id="c00e6-101">サービスが実行に使用できるメソッドを含む作成、削除、更新、およびデバイスでの delete 操作。</span><span class="sxs-lookup"><span data-stu-id="c00e6-101">Contains methods that services can use to perform create, remove, update and delete operations on devices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RegistryManager ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-102">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-102">The Device object to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-103">システムに新しいデバイスを登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-103">Register a new device with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-104">デバイス オブジェクトを生成されたキーと etag をエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-104">echoes back the Device object with the generated keys and etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-105">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-105">The Device object to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-106">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-106">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-107">システムに新しいデバイスを登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-107">Register a new device with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-108">デバイス オブジェクトを生成されたキーと etag をエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-108">echoes back the Device object with the generated keys and etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-109">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-109">The Device objects to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-110">新しいデバイスの一覧をシステムに登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-110">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-111">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-111">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-112">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-112">The Device objects to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-113">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-113">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-114">新しいデバイスの一覧をシステムに登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-114">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-115">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-115">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-116">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-116">The Device objects to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-117">新しいデバイスの一覧をシステムに登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-117">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-118">エラー メッセージの文字列配列を返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-118">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-119">登録するデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-119">The Device objects to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-120">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-120">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-121">新しいデバイスの一覧をシステムに登録します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-121">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-122">エラー メッセージの文字列配列を返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-122">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="c00e6-123">キャンセルするジョブの id</span><span class="sxs-lookup"><span data-stu-id="c00e6-123">Id of the Job to cancel</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-124">指定した ID を使用してジョブを取り消します/削除</span><span class="sxs-lookup"><span data-stu-id="c00e6-124">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="c00e6-125">キャンセルするジョブの id</span><span class="sxs-lookup"><span data-stu-id="c00e6-125">Id of the job to cancel</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-126">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-126">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-127">指定した ID を使用してジョブを取り消します/削除</span><span class="sxs-lookup"><span data-stu-id="c00e6-127">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c00e6-128">RegistryManager インスタンスを終了し、そのリソースを破棄します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-128">Closes the RegistryManager instance and disposes its resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As RegistryManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.RegistryManager" Usage="Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.RegistryManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> <span data-ttu-id="c00e6-129">Iot Hub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="c00e6-129">The Iot Hub connection string.</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-130">Iot ハブの接続文字列から、RegistryManager を作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-130">Creates a RegistryManager from the Iot Hub connection string.</span></span>
            </summary>
        <returns> <span data-ttu-id="c00e6-131">RegistryManager インスタンス。</span><span class="sxs-lookup"><span data-stu-id="c00e6-131">An RegistryManager instance.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery sqlQueryString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <summary>
            <span data-ttu-id="c00e6-132">指定したクエリの結果をフェッチする、ハンドルを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-132">Retrieves a handle through which a result for a given query can be fetched.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String, pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery (sqlQueryString, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <param name="pageSize"></param>
        <summary>
            <span data-ttu-id="c00e6-133">指定したクエリの結果をフェッチする、ハンドルを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-133">Retrieves a handle through which a result for a given query can be fetched.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="registryManager.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="registryManager.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <span data-ttu-id="c00e6-134"><c>true</c>マネージ コードとアンマネージ リソースを解放するには<c>false</c>アンマネージ リソースだけを解放します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-134"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-135">リリースでは、アンマネージし、必要に応じてマネージ リソース。</span><span class="sxs-lookup"><span data-stu-id="c00e6-135">Releases unmanaged and - optionally - managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"><span data-ttu-id="c00e6-136">コピー先 blob コンテナー URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-136">Destination blob container URI</span></span></param>
        <param name="excludeKeys"><span data-ttu-id="c00e6-137">エクスポート中に、デバイスのキーを除外するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="c00e6-137">Specifies whether to exclude the Device's Keys during the export</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-138">指定された URI で指定したコンテナーにデバイスの登録をエクスポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-138">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-139">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-139">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"><span data-ttu-id="c00e6-140">コピー先 blob コンテナー URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-140">Destination blob container URI</span></span></param>
        <param name="excludeKeys"><span data-ttu-id="c00e6-141">エクスポート中に、デバイスのキーを除外するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="c00e6-141">Specifies whether to exclude the Device's Keys during the export</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-142">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-142">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-143">指定された URI で指定したコンテナーにデバイスの登録をエクスポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-143">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-144">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-144">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, outputBlobName As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <summary>
            <span data-ttu-id="c00e6-145">指定された URI で指定したコンテナーにデバイスの登録をエクスポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-145">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-146">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-146">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="c00e6-147">指定された URI で指定したコンテナーにデバイスの登録をエクスポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-147">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-148">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-148">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDeviceAsync (deviceId As String) As Task(Of Device)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="c00e6-149">取得するデバイスの id。</span><span class="sxs-lookup"><span data-stu-id="c00e6-149">The id of the device to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-150">指定したデバイス オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-150">Retrieves the specified Device object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c00e6-151">デバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-151">The Device object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="c00e6-152">取得するデバイスの id。</span><span class="sxs-lookup"><span data-stu-id="c00e6-152">The id of the device to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-153">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-153">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-154">指定したデバイス オブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-154">Retrieves the specified Device object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c00e6-155">デバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-155">The Device object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDevicesAsync (maxCount As Integer) As Task(Of IEnumerable(Of Device))" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <summary>
            <span data-ttu-id="c00e6-156">指定したデバイスが Iot Hub のすべてのパーティションからの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-156">Retrieves specified number of devices from every Iot Hub partition.</span></span> <span data-ttu-id="c00e6-157">これは、簡略化したものと完全なリストではなくです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-157">This is an approximation and not a definitive list.</span></span> <span data-ttu-id="c00e6-158">結果の順序がありません。</span><span class="sxs-lookup"><span data-stu-id="c00e6-158">Results are not ordered.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c00e6-159">デバイスの一覧</span><span class="sxs-lookup"><span data-stu-id="c00e6-159">The list of devices</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync (maxCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="c00e6-160">指定した Iot ハブのすべてのパーティションからデバイスの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-160">Retrieves specified number of devices from every Iot hub partition.</span></span> <span data-ttu-id="c00e6-161">これは、簡略化したものと完全なリストではなくです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-161">This is an approximation and not a definitive list.</span></span> <span data-ttu-id="c00e6-162">結果の順序がありません。</span><span class="sxs-lookup"><span data-stu-id="c00e6-162">Results are not ordered.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c00e6-163">デバイスの一覧</span><span class="sxs-lookup"><span data-stu-id="c00e6-163">The list of devices</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="c00e6-164">取得するジョブ オブジェクトの id</span><span class="sxs-lookup"><span data-stu-id="c00e6-164">Id of the Job object to retrieve</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-165">指定した ID を使用してジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-165">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-166">指定されたジョブ Id で指定したジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-166">JobProperties of the job specified by the provided jobId.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="c00e6-167">取得するジョブ オブジェクトの id</span><span class="sxs-lookup"><span data-stu-id="c00e6-167">Id of the Job object to retrieve</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-168">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-168">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-169">指定した ID を使用してジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-169">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-170">指定されたジョブ Id で指定したジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-170">JobProperties of the job specified by the provided jobId.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobsAsync () As Task(Of IEnumerable(Of JobProperties))" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c00e6-171">IoT Hub をすべてのジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-171">List all jobs for the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-172">この IoT ハブのすべてのジョブの JobProperties の IEnumerable です。</span><span class="sxs-lookup"><span data-stu-id="c00e6-172">IEnumerable of JobProperties of all jobs for this IoT Hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="c00e6-173">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-173">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-174">IoT Hub をすべてのジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-174">List all jobs for the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-175">この IoT ハブのすべてのジョブの JobProperties の IEnumerable です。</span><span class="sxs-lookup"><span data-stu-id="c00e6-175">IEnumerable of JobProperties of all jobs for this IoT Hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetRegistryStatisticsAsync () As Task(Of RegistryStatistics)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c00e6-176">Iot Hub の使用状況の統計を取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-176">Gets usage statistics for the Iot Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-177">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-177">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-178">Iot Hub の使用状況の統計を取得します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-178">Gets usage statistics for the Iot Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTwinAsync (deviceId As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-179">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-179">device Id</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-180">取得<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />iot Hub から</span><span class="sxs-lookup"><span data-stu-id="c00e6-180">Gets <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> from IotHub</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-181">対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-181">Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-182">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-182">device Id</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-183">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-183">cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-184">取得<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />iot Hub から</span><span class="sxs-lookup"><span data-stu-id="c00e6-184">Gets <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> from IotHub</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-185">対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-185">Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"><span data-ttu-id="c00e6-186">ソース blob コンテナーへの URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-186">Source blob container URI</span></span></param>
        <param name="outputBlobContainerUri"><span data-ttu-id="c00e6-187">コピー先 blob コンテナー URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-187">Destination blob container URI</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-188">IoT ハブにデバイスの登録をインポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-188">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-189">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-189">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String, inputBlobName As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <summary>
            <span data-ttu-id="c00e6-190">IoT ハブにデバイスの登録をインポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-190">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-191">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-191">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"><span data-ttu-id="c00e6-192">ソース blob コンテナーへの URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-192">Source blob container URI</span></span></param>
        <param name="outputBlobContainerUri"><span data-ttu-id="c00e6-193">コピー先 blob コンテナー URI</span><span class="sxs-lookup"><span data-stu-id="c00e6-193">Destination blob container URI</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-194">タスクのキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-194">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-195">IoT ハブにデバイスの登録をインポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-195">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-196">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-196">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="c00e6-197">IoT ハブにデバイスの登録をインポートする新しい一括ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-197">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-198">新しく作成されたジョブの JobProperties します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-198">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c00e6-199">RegistryManager インスタンスを明示的に開きます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-199">Explicitly open the RegistryManager instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-200">削除するデバイスです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-200">The device to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-201">システムから以前に登録されたデバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-201">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDeviceAsync (deviceId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="c00e6-202">削除するデバイスの id。</span><span class="sxs-lookup"><span data-stu-id="c00e6-202">The id of the device to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-203">システムから以前に登録されたデバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-203">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-204">削除するデバイスです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-204">The device to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-205">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-205">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-206">システムから以前に登録されたデバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-206">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="c00e6-207">削除するデバイスの id。</span><span class="sxs-lookup"><span data-stu-id="c00e6-207">The id of the device to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-208">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-208">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-209">システムから以前に登録されたデバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-209">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-210">削除されているデバイス。</span><span class="sxs-lookup"><span data-stu-id="c00e6-210">The devices being deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-211">システムから以前に登録されたデバイスの一覧を削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-211">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-212">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-212">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-213">削除されているデバイス。</span><span class="sxs-lookup"><span data-stu-id="c00e6-213">The devices being deleted.</span></span>
            </param>
        <param name="forceRemove">
            <span data-ttu-id="c00e6-214">最後に取得された後に更新された場合でも削除するデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-214">Forces the device object to be removed even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-215">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-215">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-216">システムから以前に登録されたデバイスの一覧を削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-216">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-217">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-217">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-218">削除されているデバイス。</span><span class="sxs-lookup"><span data-stu-id="c00e6-218">The devices being deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-219">システムから以前に登録されたデバイスの一覧を削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-219">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-220">削除されているデバイス。</span><span class="sxs-lookup"><span data-stu-id="c00e6-220">The devices being deleted.</span></span>
            </param>
        <param name="forceRemove">
            <span data-ttu-id="c00e6-221">ETag 一致に関係なく削除するデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-221">Forces the device object to be removed without regard for an ETag match.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-222">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-222">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-223">システムから以前に登録されたデバイスの一覧を削除します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-223">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwin As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-224">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-224">Device Id</span></span></param>
        <param name="newTwin"><span data-ttu-id="c00e6-225">新しいの対になったオブジェクトに置き換えます</span><span class="sxs-lookup"><span data-stu-id="c00e6-225">New Twin object to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-226">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-226">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-227">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-227">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-228">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-228">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwinJson As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-229">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-229">Device Id</span></span></param>
        <param name="newTwinJson"><span data-ttu-id="c00e6-230">新しいの対になった json に置き換える</span><span class="sxs-lookup"><span data-stu-id="c00e6-230">New Twin json to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-231">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-231">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-232">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-232">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-233">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-233">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-234">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-234">Device Id</span></span></param>
        <param name="newTwin"><span data-ttu-id="c00e6-235">新しいの対になったオブジェクトに置き換えます</span><span class="sxs-lookup"><span data-stu-id="c00e6-235">New Twin object to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-236">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-236">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-237">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-237">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-238">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-238">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-239">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-239">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-240">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-240">Device Id</span></span></param>
        <param name="newTwinJson"><span data-ttu-id="c00e6-241">新しいの対になった json に置き換える</span><span class="sxs-lookup"><span data-stu-id="c00e6-241">New Twin json to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-242">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-242">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-243">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-243">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-244">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-244">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-245">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-245">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-246">更新されたフィールドを持つデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-246">The Device object with updated fields.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-247">デバイスの登録の変更可能なフィールドを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-247">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-248">更新された etag とデバイス オブジェクトをエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-248">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-249">更新されたフィールドを持つデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-249">The Device object with updated fields.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="c00e6-250">ETag 一致に関係なく置き換えられるデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-250">Forces the device object to be replaced without regard for an ETag match.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-251">デバイスの登録の変更可能なフィールドを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-251">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-252">更新された etag とデバイス オブジェクトをエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-252">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-253">更新されたフィールドを持つデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-253">The Device object with updated fields.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-254">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-254">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-255">デバイスの登録の変更可能なフィールドを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-255">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-256">更新された etag とデバイス オブジェクトをエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-256">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="c00e6-257">更新されたフィールドを持つデバイス オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c00e6-257">The Device object with updated fields.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="c00e6-258">最後に取得された後に更新された場合でも置換するデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-258">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-259">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-259">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-260">デバイスの登録の変更可能なフィールドを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-260">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-261">更新された etag とデバイス オブジェクトをエコー バック</span><span class="sxs-lookup"><span data-stu-id="c00e6-261">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-262">デバイス オブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-262">The Device objects to be updated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-263">システムとデバイスの一覧を更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-263">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-264">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-264">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-265">デバイス オブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-265">The Device objects to be updated.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="c00e6-266">最後に取得された後に更新された場合でも置換するデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-266">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-267">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-267">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-268">システムとデバイスの一覧を更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-268">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-269">BulkRegistryOperationResult オブジェクトを返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-269">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-270">デバイス オブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-270">The Device objects to be updated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-271">システムとデバイスの一覧を更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-271">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-272">エラー メッセージの文字列配列を返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-272">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="c00e6-273">デバイス オブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-273">The Device objects to be updated.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="c00e6-274">最後に取得された後に更新された場合でも置換するデバイス オブジェクトを強制します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-274">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c00e6-275">これにより、トークンは、操作をキャンセルできます。</span><span class="sxs-lookup"><span data-stu-id="c00e6-275">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c00e6-276">システムとデバイスの一覧を更新します。</span><span class="sxs-lookup"><span data-stu-id="c00e6-276">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-277">エラー メッセージの文字列配列を返します</span><span class="sxs-lookup"><span data-stu-id="c00e6-277">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, twinPatch As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-278">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-278">Device Id</span></span></param>
        <param name="twinPatch"><span data-ttu-id="c00e6-279">更新されたフィールドと対になった</span><span class="sxs-lookup"><span data-stu-id="c00e6-279">Twin with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-280">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-280">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-281">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-281">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-282">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-282">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, jsonTwinPatch As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-283">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-283">Device Id</span></span></param>
        <param name="jsonTwinPatch"><span data-ttu-id="c00e6-284">更新されたフィールドと対になった json</span><span class="sxs-lookup"><span data-stu-id="c00e6-284">Twin json with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-285">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-285">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-286">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-286">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-287">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-287">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-288">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-288">Device Id</span></span></param>
        <param name="twinPatch"><span data-ttu-id="c00e6-289">更新されたフィールドと対になった</span><span class="sxs-lookup"><span data-stu-id="c00e6-289">Twin with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-290">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-290">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-291">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-291">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-292">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-292">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-293">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-293">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="c00e6-294">デバイス Id</span><span class="sxs-lookup"><span data-stu-id="c00e6-294">Device Id</span></span></param>
        <param name="jsonTwinPatch"><span data-ttu-id="c00e6-295">更新されたフィールドと対になった json</span><span class="sxs-lookup"><span data-stu-id="c00e6-295">Twin json with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="c00e6-296">対になったの etag</span><span class="sxs-lookup"><span data-stu-id="c00e6-296">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-297">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-297">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-298">変更可能なフィールドを更新します。<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="c00e6-298">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="c00e6-299">更新の対になったインスタンス</span><span class="sxs-lookup"><span data-stu-id="c00e6-299">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async twins" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="c00e6-300">一覧の<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />更新されたフィールドを持つ s</span><span class="sxs-lookup"><span data-stu-id="c00e6-300">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-301">変更可能なフィールドの一覧を更新<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />システム内で以前に作成した s</span><span class="sxs-lookup"><span data-stu-id="c00e6-301">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-302">一括更新操作の結果</span><span class="sxs-lookup"><span data-stu-id="c00e6-302">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin), forceUpdate As Boolean) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="c00e6-303">一覧の<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />更新されたフィールドを持つ s</span><span class="sxs-lookup"><span data-stu-id="c00e6-303">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="forceUpdate"><span data-ttu-id="c00e6-304">強制的に実行、<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />最終時刻を取得されてから変更されている場合でも更新するオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-304">Forces the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> object to be updated even if it has changed since it was retrieved last time.</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-305">変更可能なフィールドの一覧を更新<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />システム内で以前に作成した s</span><span class="sxs-lookup"><span data-stu-id="c00e6-305">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-306">一括更新操作の結果</span><span class="sxs-lookup"><span data-stu-id="c00e6-306">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="c00e6-307">一覧の<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />更新されたフィールドを持つ s</span><span class="sxs-lookup"><span data-stu-id="c00e6-307">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-308">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-308">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-309">変更可能なフィールドの一覧を更新<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />システム内で以前に作成した s</span><span class="sxs-lookup"><span data-stu-id="c00e6-309">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-310">一括更新操作の結果</span><span class="sxs-lookup"><span data-stu-id="c00e6-310">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="c00e6-311">一覧の<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />更新されたフィールドを持つ s</span><span class="sxs-lookup"><span data-stu-id="c00e6-311">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="forceUpdate"><span data-ttu-id="c00e6-312">強制的に実行、<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />最終時刻を取得されてから変更されている場合でも更新するオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="c00e6-312">Forces the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> object to be updated even if it has changed since it was retrieved last time.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c00e6-313">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="c00e6-313">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c00e6-314">変更可能なフィールドの一覧を更新<see cref="T:Microsoft.Azure.Devices.Shared.Twin" />システム内で以前に作成した s</span><span class="sxs-lookup"><span data-stu-id="c00e6-314">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="c00e6-315">一括更新操作の結果</span><span class="sxs-lookup"><span data-stu-id="c00e6-315">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>