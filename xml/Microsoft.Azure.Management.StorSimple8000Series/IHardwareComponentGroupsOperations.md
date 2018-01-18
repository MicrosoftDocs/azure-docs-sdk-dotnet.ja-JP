<Type Name="IHardwareComponentGroupsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHardwareComponentGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="F#" Value="type IHardwareComponentGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c63ea-101">HardwareComponentGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c63ea-101">HardwareComponentGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c63ea-102">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c63ea-102">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="c63ea-103">ハードウェア コンポーネント グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c63ea-103">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c63ea-104">コント ローラーの電源状態では、要求を変更します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-104">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c63ea-105">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c63ea-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c63ea-106">管理者名</span><span class="sxs-lookup"><span data-stu-id="c63ea-106">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c63ea-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c63ea-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c63ea-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c63ea-109">コント ローラーの電源の状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-109">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c63ea-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c63ea-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c63ea-112">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c63ea-112">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="c63ea-113">ハードウェア コンポーネント グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c63ea-113">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c63ea-114">コント ローラーの電源状態では、要求を変更します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-114">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c63ea-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c63ea-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c63ea-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="c63ea-116">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c63ea-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c63ea-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c63ea-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c63ea-119">コント ローラーの電源の状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-119">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c63ea-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c63ea-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;" Usage="iHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="c63ea-122">デバイス名</span><span class="sxs-lookup"><span data-stu-id="c63ea-122">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c63ea-123">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="c63ea-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c63ea-124">管理者名</span><span class="sxs-lookup"><span data-stu-id="c63ea-124">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c63ea-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c63ea-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c63ea-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c63ea-127">デバイス レベルでのハードウェア コンポーネント グループを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c63ea-127">Lists the hardware component groups at device-level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c63ea-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c63ea-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c63ea-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c63ea-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>