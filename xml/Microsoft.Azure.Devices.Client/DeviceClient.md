<Type Name="DeviceClient" FullName="Microsoft.Azure.Devices.Client.DeviceClient">
  <TypeSignature Language="C#" Value="public sealed class DeviceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type DeviceClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
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
            <span data-ttu-id="0de71-101">メッセージを送信し、サービスから受信デバイスが使用できるメソッドが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0de71-101">Contains methods that a device can use to send messages to and receive from the service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.AbandonAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.AbandonAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-102">受信したメッセージをデバイスのキューに戻します</span><span class="sxs-lookup"><span data-stu-id="0de71-102">Puts a received message back onto the device queue</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-103">以前に受信したメッセージのロックの識別子</span><span class="sxs-lookup"><span data-stu-id="0de71-103">The lock identifier for the previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.AbandonAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-104">受信したメッセージをデバイスのキューに戻します</span><span class="sxs-lookup"><span data-stu-id="0de71-104">Puts a received message back onto the device queue</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-105">以前に受信したメッセージ</span><span class="sxs-lookup"><span data-stu-id="0de71-105">The previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0de71-106">DeviceClient インスタンスを閉じる</span><span class="sxs-lookup"><span data-stu-id="0de71-106">Close the DeviceClient instance</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CompleteAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CompleteAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-107">デバイスのキューから受信したメッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="0de71-107">Deletes a received message from the device queue</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-108">以前に受信したメッセージ</span><span class="sxs-lookup"><span data-stu-id="0de71-108">The previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-109">デバイスのキューから受信したメッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="0de71-109">Deletes a received message from the device queue</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-110">以前に受信したメッセージのロックの識別子</span><span class="sxs-lookup"><span data-stu-id="0de71-110">The lock identifier for the previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="0de71-111">IoT Hub の 完全修飾 DNS ホスト名</span><span class="sxs-lookup"><span data-stu-id="0de71-111">The fully-qualified DNS hostname of IoT Hub</span></span></param>
        <param name="authenticationMethod"><span data-ttu-id="0de71-112">使用する認証方法</span><span class="sxs-lookup"><span data-stu-id="0de71-112">The authentication method that is used</span></span></param>
        <summary>
            <span data-ttu-id="0de71-113">個別のパラメーターから Amqp DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-113">Create an Amqp DeviceClient from individual parameters</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-114">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-114">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="0de71-115">IoT Hub の 完全修飾 DNS ホスト名</span><span class="sxs-lookup"><span data-stu-id="0de71-115">The fully-qualified DNS hostname of IoT Hub</span></span></param>
        <param name="authenticationMethod"><span data-ttu-id="0de71-116">使用する認証方法</span><span class="sxs-lookup"><span data-stu-id="0de71-116">The authentication method that is used</span></span></param>
        <param name="transportSettings"><span data-ttu-id="0de71-117">TransportTypes とその設定の優先順位の一覧</span><span class="sxs-lookup"><span data-stu-id="0de71-117">Prioritized list of transportTypes and their settings</span></span></param>
        <summary>
            <span data-ttu-id="0de71-118">個別のパラメーターから、DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-118">Create a DeviceClient from individual parameters</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-119">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-119">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.Create (hostname, authenticationMethod, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="0de71-120">IoT Hub の 完全修飾 DNS ホスト名</span><span class="sxs-lookup"><span data-stu-id="0de71-120">The fully-qualified DNS hostname of IoT Hub</span></span></param>
        <param name="authenticationMethod"><span data-ttu-id="0de71-121">使用する認証方法</span><span class="sxs-lookup"><span data-stu-id="0de71-121">The authentication method that is used</span></span></param>
        <param name="transportType"><span data-ttu-id="0de71-122">使用 transportType (Http1 または Amqp)</span><span class="sxs-lookup"><span data-stu-id="0de71-122">The transportType used (Http1 or Amqp)</span></span></param>
        <summary>
            <span data-ttu-id="0de71-123">個別のパラメーターから、DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-123">Create a DeviceClient from individual parameters</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-124">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-124">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-125">IoT hub (DeviceId を含む) への接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-125">Connection string for the IoT hub (including DeviceId)</span></span></param>
        <summary>
            <span data-ttu-id="0de71-126">指定された接続文字列から Amqp トランスポートを使用して DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-126">Create a DeviceClient using Amqp transport from the specified connection string</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-127">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-127">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-128">IoT hub (DeviceId) との接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-128">Connection string for the IoT hub (with DeviceId)</span></span></param>
        <param name="transportSettings"><span data-ttu-id="0de71-129">トランスポートとその設定の優先順位の一覧</span><span class="sxs-lookup"><span data-stu-id="0de71-129">Prioritized list of transports and their settings</span></span></param>
        <summary>
            <span data-ttu-id="0de71-130">トランスポートの優先順位付けされた一覧を使用して、指定された接続文字列から DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-130">Create DeviceClient from the specified connection string using a prioritized list of transports</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-131">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-131">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-132">IoT hub (DeviceId を含む) への接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-132">Connection string for the IoT hub (including DeviceId)</span></span></param>
        <param name="transportType"><span data-ttu-id="0de71-133">Amqp または Http トランスポートを使用するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="0de71-133">Specifies whether Amqp or Http transport is used</span></span></param>
        <summary>
            <span data-ttu-id="0de71-134">指定された接続文字列を使用して、指定したトランスポートの種類 (PCL) のみの Http トランスポートが許可されてから DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-134">Create DeviceClient from the specified connection string using the specified transport type (PCL) Only Http transport is allowed</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-135">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-135">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, deviceId As String) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-136">IoT hub (DeviceId) なしの IoT ハブ スコープ接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-136">IoT Hub-Scope Connection string for the IoT hub (without DeviceId)</span></span></param>
        <param name="deviceId"><span data-ttu-id="0de71-137">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="0de71-137">Id of the Device</span></span></param>
        <summary>
            <span data-ttu-id="0de71-138">作成、DeviceClient 指定された接続文字列からの Http トランスポートを使用して DeviceClient から指定された接続文字列 (WinRT) Amqp トランスポートを使用して作成</span><span class="sxs-lookup"><span data-stu-id="0de71-138">Create a DeviceClient using Amqp transport from the specified connection string (WinRT) Create a DeviceClient using Http transport from the specified connection string</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-139">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-139">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId, Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId, class Microsoft.Azure.Devices.Client.ITransportSettings[] transportSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String,Microsoft.Azure.Devices.Client.ITransportSettings[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, deviceId As String, transportSettings As ITransportSettings()) As DeviceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.Azure.Devices.Client.ITransportSettings[] -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId, transportSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="transportSettings" Type="Microsoft.Azure.Devices.Client.ITransportSettings[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-140">IoT hub (DeviceId) なしの接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-140">Connection string for the IoT hub (without DeviceId)</span></span></param>
        <param name="deviceId"><span data-ttu-id="0de71-141">デバイスの ID</span><span class="sxs-lookup"><span data-stu-id="0de71-141">Id of the device</span></span></param>
        <param name="transportSettings"><span data-ttu-id="0de71-142">TransportTypes とその設定の優先順位の一覧</span><span class="sxs-lookup"><span data-stu-id="0de71-142">Prioritized list of transportTypes and their settings</span></span></param>
        <summary>
            <span data-ttu-id="0de71-143">トランスポートの優先順位付けされた一覧を使用して、指定された接続文字列から DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-143">Create DeviceClient from the specified connection string using the prioritized list of transports</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-144">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-144">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString (string connectionString, string deviceId, Microsoft.Azure.Devices.Client.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.DeviceClient CreateFromConnectionString(string connectionString, string deviceId, valuetype Microsoft.Azure.Devices.Client.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString(System.String,System.String,Microsoft.Azure.Devices.Client.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.Azure.Devices.Client.TransportType -&gt; Microsoft.Azure.Devices.Client.DeviceClient" Usage="Microsoft.Azure.Devices.Client.DeviceClient.CreateFromConnectionString (connectionString, deviceId, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.DeviceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.Client.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0de71-145">IoT hub (DeviceId) なしの IoT ハブ スコープ接続文字列</span><span class="sxs-lookup"><span data-stu-id="0de71-145">IoT Hub-Scope Connection string for the IoT hub (without DeviceId)</span></span></param>
        <param name="deviceId"><span data-ttu-id="0de71-146">デバイスの ID</span><span class="sxs-lookup"><span data-stu-id="0de71-146">Id of the device</span></span></param>
        <param name="transportType"><span data-ttu-id="0de71-147">使用 transportType (Http1 または Amqp)</span><span class="sxs-lookup"><span data-stu-id="0de71-147">The transportType used (Http1 or Amqp)</span></span></param>
        <summary>
            <span data-ttu-id="0de71-148">指定したトランスポートの種類を使用して、指定された接続文字列から DeviceClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="0de71-148">Create DeviceClient from the specified connection string using the specified transport type</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-149">DeviceClient</span><span class="sxs-lookup"><span data-stu-id="0de71-149">DeviceClient</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOperationTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public const uint DefaultOperationTimeoutInMilliseconds = 240000;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal unsigned int32 DefaultOperationTimeoutInMilliseconds = (240000)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Client.DeviceClient.DefaultOperationTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultOperationTimeoutInMilliseconds As UInteger  = 240000" />
      <MemberSignature Language="F#" Value="val mutable DefaultOperationTimeoutInMilliseconds : uint32" Usage="Microsoft.Azure.Devices.Client.DeviceClient.DefaultOperationTimeoutInMilliseconds" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <MemberValue>240000</MemberValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticSamplingPercentage">
      <MemberSignature Language="C#" Value="public int DiagnosticSamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiagnosticSamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.DiagnosticSamplingPercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticSamplingPercentage As Integer" />
      <MemberSignature Language="F#" Value="member this.DiagnosticSamplingPercentage : int with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.DiagnosticSamplingPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="deviceClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.GetTwinAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTwinAsync () As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="member this.GetTwinAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="deviceClient.GetTwinAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0de71-150">現在のデバイスのデバイスの対になったオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="0de71-150">Retrieve a device twin object for the current device.</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-151">現在のデバイスのデバイスの対になったオブジェクト</span><span class="sxs-lookup"><span data-stu-id="0de71-151">The device twin object for the current device</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="deviceClient.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0de71-152">DeviceClient インスタンスを明示的に開きます。</span><span class="sxs-lookup"><span data-stu-id="0de71-152">Explicitly open the DeviceClient instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeoutInMilliseconds">
      <MemberSignature Language="C#" Value="public uint OperationTimeoutInMilliseconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 OperationTimeoutInMilliseconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.OperationTimeoutInMilliseconds" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeoutInMilliseconds As UInteger" />
      <MemberSignature Language="F#" Value="member this.OperationTimeoutInMilliseconds : uint32 with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.OperationTimeoutInMilliseconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0de71-153">操作の再試行で使用されるタイムアウト値を格納します。</span><span class="sxs-lookup"><span data-stu-id="0de71-153">Stores the timeout used in the operation retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductInfo">
      <MemberSignature Language="C#" Value="public string ProductInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProductInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.ProductInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductInfo As String" />
      <MemberSignature Language="F#" Value="member this.ProductInfo : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.ProductInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0de71-154">IoT Hub に送信されるユーザー エージェント文字列に追加されるカスタムの製品情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="0de71-154">Stores custom product information that will be appended to the user agent string that is sent to IoT Hub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;" Usage="deviceClient.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0de71-155">既定のタイムアウトを使用してデバイスのキューからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="0de71-155">Receive a message from the device queue using the default timeout.</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-156">受信メッセージまたは既定のタイムアウトするまでメッセージがなかった場合は null</span><span class="sxs-lookup"><span data-stu-id="0de71-156">The receive message or null if there was no message until the default timeout</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; ReceiveAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (timeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;" Usage="deviceClient.ReceiveAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Client.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-157">タイムアウトを指定して、デバイスのキューからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="0de71-157">Receive a message from the device queue with the specified timeout</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-158">受信メッセージまたは指定された時間が経過するまで、メッセージがなかった場合は null</span><span class="sxs-lookup"><span data-stu-id="0de71-158">The receive message or null if there was no message until the specified time has elapsed</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RejectAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RejectAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.RejectAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.RejectAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.RejectAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-159">デバイスのキューから受信したメッセージを削除し、メッセージが処理されなかったことをサーバーを示します。</span><span class="sxs-lookup"><span data-stu-id="0de71-159">Deletes a received message from the device queue and indicates to the server that the message could not be processed.</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-160">以前に受信したメッセージのロックの識別子</span><span class="sxs-lookup"><span data-stu-id="0de71-160">The lock identifier for the previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RejectAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RejectAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.RejectAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RejectAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RejectAsync : string -&gt; System.Threading.Tasks.Task" Usage="deviceClient.RejectAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-161">デバイスのキューから受信したメッセージを削除し、メッセージが処理されなかったことをサーバーを示します。</span><span class="sxs-lookup"><span data-stu-id="0de71-161">Deletes a received message from the device queue and indicates to the server that the message could not be processed.</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-162">以前に受信したメッセージ</span><span class="sxs-lookup"><span data-stu-id="0de71-162">The previously received message</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.RetryPolicyType RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.Client.RetryPolicyType RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceClient.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicyType" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Devices.Client.RetryPolicyType with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceClient.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method has been deprecated.  Please use Microsoft.Azure.Devices.Client.SetRetryPolicy(IRetryPolicy retryPolicy) instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.RetryPolicyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0de71-163">操作の再試行で使用される再試行戦略を格納します。</span><span class="sxs-lookup"><span data-stu-id="0de71-163">Stores the retry strategy used in the operation retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendEventAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendEventAsync (Microsoft.Azure.Devices.Client.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendEventAsync(class Microsoft.Azure.Devices.Client.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SendEventAsync(Microsoft.Azure.Devices.Client.Message)" />
      <MemberSignature Language="F#" Value="member this.SendEventAsync : Microsoft.Azure.Devices.Client.Message -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SendEventAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Client.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-164">デバイスのハブにイベントを送信します。</span><span class="sxs-lookup"><span data-stu-id="0de71-164">Sends an event to device hub</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-165">イベントが含まれるメッセージ</span><span class="sxs-lookup"><span data-stu-id="0de71-165">The message containing the event</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendEventBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendEventBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Client.Message&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendEventBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Client.Message&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SendEventBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Client.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendEventBatchAsync (messages As IEnumerable(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendEventBatchAsync : seq&lt;Microsoft.Azure.Devices.Client.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SendEventBatchAsync messages" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Client.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-166">デバイスのハブにイベントのバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="0de71-166">Sends a batch of events to device hub</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-167">イベントを含むタスク</span><span class="sxs-lookup"><span data-stu-id="0de71-167">The task containing the event</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetConnectionStatusChangesHandler">
      <MemberSignature Language="C#" Value="public void SetConnectionStatusChangesHandler (Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler statusChangesHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetConnectionStatusChangesHandler(class Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler statusChangesHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetConnectionStatusChangesHandler(Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetConnectionStatusChangesHandler (statusChangesHandler As ConnectionStatusChangesHandler)" />
      <MemberSignature Language="F#" Value="member this.SetConnectionStatusChangesHandler : Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler -&gt; unit" Usage="deviceClient.SetConnectionStatusChangesHandler statusChangesHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="statusChangesHandler" Type="Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler" />
      </Parameters>
      <Docs>
        <param name="statusChangesHandler">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-168">接続状態の変更のコールバックを新しいデリゲートを登録します。</span><span class="sxs-lookup"><span data-stu-id="0de71-168">Registers a new delegate for the connection status changed callback.</span></span> <span data-ttu-id="0de71-169">デリゲートは既に関連付けられている場合は、新しいデリゲートに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="0de71-169">If a delegate is already associated, it will be replaced with the new delegate.</span></span>
            <span data-ttu-id="0de71-170"><param name="statusChangesHandler">デリゲートを関連付けるためのメソッドの名前です。</param></span><span class="sxs-lookup"><span data-stu-id="0de71-170"><param name="statusChangesHandler">The name of the method to associate with the delegate.</param></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetDesiredPropertyUpdateCallback">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetDesiredPropertyUpdateCallback (Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetDesiredPropertyUpdateCallback(class Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetDesiredPropertyUpdateCallback(Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetDesiredPropertyUpdateCallback (callback As DesiredPropertyUpdateCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetDesiredPropertyUpdateCallback : Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetDesiredPropertyUpdateCallback (callback, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Please use SetDesiredPropertyUpdateCallbackAsync.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="0de71-171">状態の更新が受信および適用された後に呼び出すコールバック</span><span class="sxs-lookup"><span data-stu-id="0de71-171">Callback to call after the state update has been received and applied</span></span></param>
        <param name="userContext"><span data-ttu-id="0de71-172">コールバックに渡されるコンテキスト オブジェクト</span><span class="sxs-lookup"><span data-stu-id="0de71-172">Context object that will be passed into callback</span></span></param>
        <summary>
            <span data-ttu-id="0de71-173">クライアントがサービスから状態の更新 (必要なまたは報告) を受信するたびに呼び出されるコールバックを設定します。</span><span class="sxs-lookup"><span data-stu-id="0de71-173">Set a callback that will be called whenever the client receives a state update (desired or reported) from the service.</span></span>  <span data-ttu-id="0de71-174">これは、サービスの修正プログラムのトピックにサブスクライブすることの副作用です。</span><span class="sxs-lookup"><span data-stu-id="0de71-174">This has the side-effect of subscribing to the PATCH topic on the service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetDesiredPropertyUpdateCallbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetDesiredPropertyUpdateCallbackAsync (Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetDesiredPropertyUpdateCallbackAsync(class Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback callback, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetDesiredPropertyUpdateCallbackAsync(Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetDesiredPropertyUpdateCallbackAsync (callback As DesiredPropertyUpdateCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetDesiredPropertyUpdateCallbackAsync : Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetDesiredPropertyUpdateCallbackAsync (callback, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="0de71-175">状態の更新が受信および適用された後に呼び出すコールバック</span><span class="sxs-lookup"><span data-stu-id="0de71-175">Callback to call after the state update has been received and applied</span></span></param>
        <param name="userContext"><span data-ttu-id="0de71-176">コールバックに渡されるコンテキスト オブジェクト</span><span class="sxs-lookup"><span data-stu-id="0de71-176">Context object that will be passed into callback</span></span></param>
        <summary>
            <span data-ttu-id="0de71-177">クライアントがサービスから状態の更新 (必要なまたは報告) を受信するたびに呼び出されるコールバックを設定します。</span><span class="sxs-lookup"><span data-stu-id="0de71-177">Set a callback that will be called whenever the client receives a state update (desired or reported) from the service.</span></span>  <span data-ttu-id="0de71-178">これは、サービスの修正プログラムのトピックにサブスクライブすることの副作用です。</span><span class="sxs-lookup"><span data-stu-id="0de71-178">This has the side-effect of subscribing to the PATCH topic on the service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodDefaultHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetMethodDefaultHandlerAsync (Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetMethodDefaultHandlerAsync(class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodDefaultHandlerAsync(Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetMethodDefaultHandlerAsync (methodHandler As MethodCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetMethodDefaultHandlerAsync : Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetMethodDefaultHandlerAsync (methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Devices.Client.DeviceClient/&lt;SetMethodDefaultHandlerAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodHandler"><span data-ttu-id="0de71-179">クラウド サービスで、メソッドが呼び出され、デリゲートがないときに使用されるデリゲートでは、そのメソッド名が登録されます。</span><span class="sxs-lookup"><span data-stu-id="0de71-179">The delegate to be used when a method is called by the cloud service and there is no delegate registered for that method name.</span></span></param>
        <param name="userContext"><span data-ttu-id="0de71-180">クライアント コードによって解釈されるジェネリック パラメーター。</span><span class="sxs-lookup"><span data-stu-id="0de71-180">Generic parameter to be interpreted by the client code.</span></span></param>
        <summary>
            <span data-ttu-id="0de71-181">その名前の登録されているデリゲートがないメソッドに対して呼び出される新しいデリゲートを登録します。</span><span class="sxs-lookup"><span data-stu-id="0de71-181">Registers a new delegate that is called for a method that doesn't have a delegate registered for its name.</span></span> <span data-ttu-id="0de71-182">既定のデリゲートは既に登録されている場合は、新しいデリゲートを使用すると置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="0de71-182">If a default delegate is already registered it will replace with the new delegate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodHandler">
      <MemberSignature Language="C#" Value="public void SetMethodHandler (string methodName, Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMethodHandler(string methodName, class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodHandler(System.String,Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMethodHandler (methodName As String, methodHandler As MethodCallback, userContext As Object)" />
      <MemberSignature Language="F#" Value="member this.SetMethodHandler : string * Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; unit" Usage="deviceClient.SetMethodHandler (methodName, methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Please use SetMethodHandlerAsync.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodName">To be added.</param>
        <param name="methodHandler">To be added.</param>
        <param name="userContext">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-183">名前付きのメソッドの新しい delgate を登録します。</span><span class="sxs-lookup"><span data-stu-id="0de71-183">Registers a new delgate for the named method.</span></span> <span data-ttu-id="0de71-184">デリゲートが既に名前付きメソッドに関連付けられている場合は、新しいデリゲートに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="0de71-184">If a delegate is already associated with the named method, it will be replaced with the new delegate.</span></span>
            <span data-ttu-id="0de71-185"><param name="methodName">デリゲートを関連付けるためのメソッドの名前です。</param><param name="methodHandler">クラウド サービスによって指定された名前を持つメソッドが呼び出されたときに使用されるデリゲート</param>。<param name="userContext">クライアント コードによって解釈されるジェネリック パラメーター。</param></span><span class="sxs-lookup"><span data-stu-id="0de71-185"><param name="methodName">The name of the method to associate with the delegate.</param><param name="methodHandler">The delegate to be used when a method with the given name is called by the cloud service.</param><param name="userContext">generic parameter to be interpreted by the client code.</param></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMethodHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetMethodHandlerAsync (string methodName, Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetMethodHandlerAsync(string methodName, class Microsoft.Azure.Devices.Client.MethodCallback methodHandler, object userContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetMethodHandlerAsync(System.String,Microsoft.Azure.Devices.Client.MethodCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetMethodHandlerAsync (methodName As String, methodHandler As MethodCallback, userContext As Object) As Task" />
      <MemberSignature Language="F#" Value="member this.SetMethodHandlerAsync : string * Microsoft.Azure.Devices.Client.MethodCallback * obj -&gt; System.Threading.Tasks.Task" Usage="deviceClient.SetMethodHandlerAsync (methodName, methodHandler, userContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Devices.Client.DeviceClient/&lt;SetMethodHandlerAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="methodHandler" Type="Microsoft.Azure.Devices.Client.MethodCallback" />
        <Parameter Name="userContext" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodName">To be added.</param>
        <param name="methodHandler">To be added.</param>
        <param name="userContext">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-186">名前付きのメソッドの新しい delgate を登録します。</span><span class="sxs-lookup"><span data-stu-id="0de71-186">Registers a new delgate for the named method.</span></span> <span data-ttu-id="0de71-187">デリゲートが既に名前付きメソッドに関連付けられている場合は、新しいデリゲートに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="0de71-187">If a delegate is already associated with the named method, it will be replaced with the new delegate.</span></span>
            <span data-ttu-id="0de71-188"><param name="methodName">デリゲートを関連付けるためのメソッドの名前です。</param><param name="methodHandler">クラウド サービスによって指定された名前を持つメソッドが呼び出されたときに使用されるデリゲート</param>。<param name="userContext">クライアント コードによって解釈されるジェネリック パラメーター。</param></span><span class="sxs-lookup"><span data-stu-id="0de71-188"><param name="methodName">The name of the method to associate with the delegate.</param><param name="methodHandler">The delegate to be used when a method with the given name is called by the cloud service.</param><param name="userContext">generic parameter to be interpreted by the client code.</param></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetRetryPolicy">
      <MemberSignature Language="C#" Value="public void SetRetryPolicy (Microsoft.Azure.Devices.Client.IRetryPolicy retryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetRetryPolicy(class Microsoft.Azure.Devices.Client.IRetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.SetRetryPolicy(Microsoft.Azure.Devices.Client.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetRetryPolicy (retryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="member this.SetRetryPolicy : Microsoft.Azure.Devices.Client.IRetryPolicy -&gt; unit" Usage="deviceClient.SetRetryPolicy retryPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Devices.Client.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="retryPolicy">To be added.</param>
        <summary>
            <span data-ttu-id="0de71-189">操作の再試行で使用される再試行ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="0de71-189">Sets the retry policy used in the operation retries.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportedPropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateReportedPropertiesAsync (Microsoft.Azure.Devices.Shared.TwinCollection reportedProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateReportedPropertiesAsync(class Microsoft.Azure.Devices.Shared.TwinCollection reportedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.UpdateReportedPropertiesAsync(Microsoft.Azure.Devices.Shared.TwinCollection)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateReportedPropertiesAsync (reportedProperties As TwinCollection) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateReportedPropertiesAsync : Microsoft.Azure.Devices.Shared.TwinCollection -&gt; System.Threading.Tasks.Task" Usage="deviceClient.UpdateReportedPropertiesAsync reportedProperties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportedProperties" Type="Microsoft.Azure.Devices.Shared.TwinCollection" />
      </Parameters>
      <Docs>
        <param name="reportedProperties"><span data-ttu-id="0de71-190">報告されたプロパティをプッシュするには</span><span class="sxs-lookup"><span data-stu-id="0de71-190">Reported properties to push</span></span></param>
        <summary>
            <span data-ttu-id="0de71-191">プッシュがサービスにまでのプロパティの変更を報告します。</span><span class="sxs-lookup"><span data-stu-id="0de71-191">Push reported property changes up to the service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadToBlobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UploadToBlobAsync (string blobName, System.IO.Stream source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UploadToBlobAsync(string blobName, class System.IO.Stream source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceClient.UploadToBlobAsync(System.String,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function UploadToBlobAsync (blobName As String, source As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.UploadToBlobAsync : string * System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="deviceClient.UploadToBlobAsync (blobName, source)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="source" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="blobName"></param>
        <param name="source"></param>
        <summary>
            <span data-ttu-id="0de71-192">そのデバイスを iot Hub に関連付けられているストレージ アカウント内にブロック blob にストリームをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="0de71-192">Uploads a stream to a block blob in a storage account associated with the IoTHub for that device.</span></span>
            <span data-ttu-id="0de71-193">Blob が既に存在する場合は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="0de71-193">If the blob already exists, it will be overwritten.</span></span>
            </summary>
        <returns><span data-ttu-id="0de71-194">AsncTask</span><span class="sxs-lookup"><span data-stu-id="0de71-194">AsncTask</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>