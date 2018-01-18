<Type Name="DevicesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DevicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DevicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DevicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DevicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7755e-101">DevicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7755e-101">Extension methods for DevicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizeForServiceEncryptionKeyRollover">
      <MemberSignature Language="C#" Value="public static void AuthorizeForServiceEncryptionKeyRollover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AuthorizeForServiceEncryptionKeyRollover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRollover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub AuthorizeForServiceEncryptionKeyRollover (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member AuthorizeForServiceEncryptionKeyRollover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRollover (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-103">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-103">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-105">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-106">サービス データ暗号化キーのロール オーバーの指定されたデバイスを認証します。</span><span class="sxs-lookup"><span data-stu-id="7755e-106">Authorizes the specified device for service data encryption key rollover.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizeForServiceEncryptionKeyRolloverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AuthorizeForServiceEncryptionKeyRolloverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AuthorizeForServiceEncryptionKeyRolloverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRolloverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AuthorizeForServiceEncryptionKeyRolloverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.AuthorizeForServiceEncryptionKeyRolloverAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;AuthorizeForServiceEncryptionKeyRolloverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-108">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-108">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-109">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-109">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-110">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-110">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-112">サービス データ暗号化キーのロール オーバーの指定されたデバイスを認証します。</span><span class="sxs-lookup"><span data-stu-id="7755e-112">Authorizes the specified device for service data encryption key rollover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConfigure">
      <MemberSignature Language="C#" Value="public static void BeginConfigure (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginConfigure(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigure(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginConfigure (operations As IDevicesOperations, parameters As ConfigureDeviceRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginConfigure : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigure (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-113">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-114">デバイスを構成する最小のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7755e-114">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-116">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-117">デバイスを使用する前に、最小限のセットアップを完了します。</span><span class="sxs-lookup"><span data-stu-id="7755e-117">Complete minimal setup before using the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConfigureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginConfigureAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginConfigureAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigureAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginConfigureAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginConfigureAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginConfigureAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-118">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-119">デバイスを構成する最小のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7755e-119">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-120">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-120">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-121">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-121">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-123">デバイスを使用する前に、最小限のセットアップを完了します。</span><span class="sxs-lookup"><span data-stu-id="7755e-123">Complete minimal setup before using the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeactivate">
      <MemberSignature Language="C#" Value="public static void BeginDeactivate (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDeactivate(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivate(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDeactivate (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDeactivate : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-124">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-125">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-125">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-126">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-126">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-127">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-127">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-128">デバイスが非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="7755e-128">Deactivates the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeactivateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeactivateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeactivateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeactivateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginDeactivateAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-129">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-130">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-130">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-131">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-131">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-132">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-132">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-134">デバイスが非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="7755e-134">Deactivates the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDelete (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-135">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-136">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-136">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-137">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-137">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-138">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-138">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-139">デバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7755e-139">Deletes the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginDeleteAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-140">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-141">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-141">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-142">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-142">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-143">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-143">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-145">デバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7755e-145">Deletes the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailover">
      <MemberSignature Language="C#" Value="public static void BeginFailover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginFailover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginFailover (operations As IDevicesOperations, sourceDeviceName As String, parameters As FailoverRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginFailover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailover (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-146">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-147">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-147">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-148">フェールオーバーできません。 ソース デバイスとボリューム コンテナーの一覧を含む FailoverRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-148">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-149">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-149">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-150">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-150">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-151">フェールオーバーのターゲット デバイスに指定されたソース デバイスからのボリューム コンテナーのセット。</span><span class="sxs-lookup"><span data-stu-id="7755e-151">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginFailoverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginFailoverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailoverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginFailoverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginFailoverAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginFailoverAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-152">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-153">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-153">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-154">フェールオーバーできません。 ソース デバイスとボリューム コンテナーの一覧を含む FailoverRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-154">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-155">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-156">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-156">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-158">フェールオーバーのターゲット デバイスに指定されたソース デバイスからのボリューム コンテナーのセット。</span><span class="sxs-lookup"><span data-stu-id="7755e-158">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginInstallUpdates">
      <MemberSignature Language="C#" Value="public static void BeginInstallUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginInstallUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginInstallUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginInstallUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-159">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-160">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-160">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-161">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-161">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-162">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-162">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-163">ダウンロードし、デバイスの更新プログラムをインストールします。</span><span class="sxs-lookup"><span data-stu-id="7755e-163">Downloads and installs the updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginInstallUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginInstallUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginInstallUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginInstallUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginInstallUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginInstallUpdatesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-164">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-165">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-165">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-166">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-167">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-167">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-169">ダウンロードし、デバイスの更新プログラムをインストールします。</span><span class="sxs-lookup"><span data-stu-id="7755e-169">Downloads and installs the updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginScanForUpdates">
      <MemberSignature Language="C#" Value="public static void BeginScanForUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginScanForUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginScanForUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginScanForUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-170">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-171">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-171">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-172">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-172">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-173">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-173">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-174">デバイスの更新プログラムをスキャンします。</span><span class="sxs-lookup"><span data-stu-id="7755e-174">Scans for updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginScanForUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginScanForUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginScanForUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginScanForUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.BeginScanForUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;BeginScanForUpdatesAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-175">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-176">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-176">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-177">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-178">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-180">デバイスの更新プログラムをスキャンします。</span><span class="sxs-lookup"><span data-stu-id="7755e-180">Scans for updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static void Configure (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Configure(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Configure(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Configure (operations As IDevicesOperations, parameters As ConfigureDeviceRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Configure : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Configure (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-181">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-182">デバイスを構成する最小のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7755e-182">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-183">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-183">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-184">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-184">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-185">デバイスを使用する前に、最小限のセットアップを完了します。</span><span class="sxs-lookup"><span data-stu-id="7755e-185">Complete minimal setup before using the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ConfigureAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ConfigureAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ConfigureAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConfigureAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ConfigureAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ConfigureAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-186">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-187">デバイスを構成する最小のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7755e-187">The minimal properties to configure a device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-188">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-188">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-189">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-189">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-191">デバイスを使用する前に、最小限のセットアップを完了します。</span><span class="sxs-lookup"><span data-stu-id="7755e-191">Complete minimal setup before using the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deactivate">
      <MemberSignature Language="C#" Value="public static void Deactivate (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Deactivate(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Deactivate(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Deactivate (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Deactivate : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Deactivate (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-192">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-193">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-193">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-194">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-194">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-195">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-195">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-196">デバイスが非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="7755e-196">Deactivates the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeactivateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeactivateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeactivateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeactivateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeactivateAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;DeactivateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-197">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-198">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-198">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-199">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-199">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-200">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-200">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-202">デバイスが非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="7755e-202">Deactivates the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Delete (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-203">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-204">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-204">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-205">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-205">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-206">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-206">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-207">デバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7755e-207">Deletes the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.DeleteAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-208">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-209">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-209">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-210">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-210">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-211">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-211">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-213">デバイスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7755e-213">Deletes the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failover">
      <MemberSignature Language="C#" Value="public static void Failover (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Failover(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Failover(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Failover (operations As IDevicesOperations, sourceDeviceName As String, parameters As FailoverRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Failover : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Failover (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-214">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-215">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-215">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-216">フェールオーバーできません。 ソース デバイスとボリューム コンテナーの一覧を含む FailoverRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-216">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-217">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-217">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-218">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-218">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-219">フェールオーバーのターゲット デバイスに指定されたソース デバイスからのボリューム コンテナーのセット。</span><span class="sxs-lookup"><span data-stu-id="7755e-219">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task FailoverAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task FailoverAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.FailoverAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member FailoverAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.FailoverAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;FailoverAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-220">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-221">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-221">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-222">フェールオーバーできません。 ソース デバイスとボリューム コンテナーの一覧を含む FailoverRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-222">FailoverRequest containing the source device and the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-223">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-223">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-224">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-224">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-226">フェールオーバーのターゲット デバイスに指定されたソース デバイスからのボリューム コンテナーのセット。</span><span class="sxs-lookup"><span data-stu-id="7755e-226">Failovers a set of volume containers from a specified source device to a target device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Device Get (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Device Get(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String, Optional expand As String = null) As Device" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Get (operations, deviceName, resourceGroupName, managerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Device</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-227">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-228">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-228">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-229">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-229">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-230">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-230">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7755e-231">$ を指定順に展開、デバイスまたは $ に関連するその他のフィールドを設定するための詳細を = 展開 rolloverdetails サービス データ暗号化キーのロール オーバー デバイス上に関連するその他のフィールドに入力を =</span><span class="sxs-lookup"><span data-stu-id="7755e-231">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-232">指定したデバイスのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-232">Returns the properties of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetAsync (operations, deviceName, resourceGroupName, managerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-233">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-234">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-234">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-235">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-235">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-236">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-236">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7755e-237">$ を指定順に展開、デバイスまたは $ に関連するその他のフィールドを設定するための詳細を = 展開 rolloverdetails サービス データ暗号化キーのロール オーバー デバイス上に関連するその他のフィールドに入力を =</span><span class="sxs-lookup"><span data-stu-id="7755e-237">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-239">指定したデバイスのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-239">Returns the properties of the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpdateSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Updates GetUpdateSummary (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Updates GetUpdateSummary(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummary(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetUpdateSummary (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As Updates" />
      <MemberSignature Language="F#" Value="static member GetUpdateSummary : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Updates" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummary (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Updates</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-240">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-241">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-241">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-242">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-242">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-243">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-243">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-244">更新プログラムを返します、指定したデバイス名の概要です。</span><span class="sxs-lookup"><span data-stu-id="7755e-244">Returns the update summary of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpdateSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt; GetUpdateSummaryAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt; GetUpdateSummaryAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummaryAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetUpdateSummaryAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.GetUpdateSummaryAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;GetUpdateSummaryAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Updates&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-245">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-246">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-246">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-247">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-247">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-248">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-248">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-250">更新プログラムを返します、指定したデバイス名の概要です。</span><span class="sxs-lookup"><span data-stu-id="7755e-250">Returns the update summary of the specified device name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallUpdates">
      <MemberSignature Language="C#" Value="public static void InstallUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void InstallUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub InstallUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member InstallUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-251">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-252">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-252">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-253">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-253">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-254">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-254">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-255">ダウンロードし、デバイスの更新プログラムをインストールします。</span><span class="sxs-lookup"><span data-stu-id="7755e-255">Downloads and installs the updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task InstallUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task InstallUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member InstallUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.InstallUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;InstallUpdatesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-256">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-257">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-257">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-258">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-258">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-259">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-259">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-260">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-261">ダウンロードし、デバイスの更新プログラムをインストールします。</span><span class="sxs-lookup"><span data-stu-id="7755e-261">Downloads and installs the updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IDevicesOperations, resourceGroupName As String, managerName As String, Optional expand As String = null) As IEnumerable(Of Device)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManager (operations, resourceGroupName, managerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-262">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-263">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-263">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-264">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-264">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7755e-265">$ を指定順に展開、デバイスまたは $ に関連するその他のフィールドを設定するための詳細を = 展開 rolloverdetails サービス データ暗号化キーのロール オーバー デバイス上に関連するその他のフィールドに入力を =</span><span class="sxs-lookup"><span data-stu-id="7755e-265">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-266">指定したマネージャーのデバイスの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-266">Returns the list of devices for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string resourceGroupName, string managerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListByManagerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-268">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-268">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-269">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-269">The manager name</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7755e-270">$ を指定順に展開、デバイスまたは $ に関連するその他のフィールドを設定するための詳細を = 展開 rolloverdetails サービス データ暗号化キーのロール オーバー デバイス上に関連するその他のフィールドに入力を =</span><span class="sxs-lookup"><span data-stu-id="7755e-270">Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-272">指定したマネージャーのデバイスの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-272">Returns the list of devices for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverSets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt; ListFailoverSets (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt; ListFailoverSets(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSets(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFailoverSets (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of FailoverSet)" />
      <MemberSignature Language="F#" Value="static member ListFailoverSets : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSets (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-273">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-274">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-274">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-275">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-275">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-276">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-276">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-277">特定のデバイスのすべてのフェールオーバー セットと、フェールオーバーに参加するための適格性を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-277">Returns all failover sets for a given device and their eligibility for participating in a failover.</span></span> <span data-ttu-id="7755e-278">フェールオーバー セットは、あるフェールオーバーされたデータの整合性を維持するために 1 つの単位としてする必要があるボリューム コンテナーのセットを指します。</span><span class="sxs-lookup"><span data-stu-id="7755e-278">A failover set refers to a set of volume containers that need to be failed-over as a single unit to maintain data integrity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverSetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt; ListFailoverSetsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt; ListFailoverSetsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSetsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFailoverSetsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverSetsAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListFailoverSetsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-279">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-279">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-280">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-280">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-281">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-281">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-282">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-282">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-283">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-283">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-284">特定のデバイスのすべてのフェールオーバー セットと、フェールオーバーに参加するための適格性を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-284">Returns all failover sets for a given device and their eligibility for participating in a failover.</span></span> <span data-ttu-id="7755e-285">フェールオーバー セットは、あるフェールオーバーされたデータの整合性を維持するために 1 つの単位としてする必要があるボリューム コンテナーのセットを指します。</span><span class="sxs-lookup"><span data-stu-id="7755e-285">A failover set refers to a set of volume containers that need to be failed-over as a single unit to maintain data integrity.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverTargets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt; ListFailoverTargets (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt; ListFailoverTargets(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargets(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFailoverTargets (operations As IDevicesOperations, sourceDeviceName As String, parameters As ListFailoverTargetsRequest, resourceGroupName As String, managerName As String) As IEnumerable(Of FailoverTarget)" />
      <MemberSignature Language="F#" Value="static member ListFailoverTargets : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargets (operations, sourceDeviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-286">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-286">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-287">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-287">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-288">フェールオーバーするボリューム コンテナーの一覧を含む ListFailoverTargetsRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-288">ListFailoverTargetsRequest containing the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-289">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-289">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-290">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-290">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-291">ソース デバイスからはフェールオーバーするボリューム コンテナーの一覧を指定するには、このメソッドは、そのリソースの下のすべてのデバイスのフェールオーバー ターゲットとしての対象となる結果を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-291">Given a list of volume containers to be failed over from a source device, this method returns the eligibility result, as a failover target, for all devices under that resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFailoverTargetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt; ListFailoverTargetsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt; ListFailoverTargetsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string sourceDeviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargetsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFailoverTargetsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListFailoverTargetsAsync (operations, sourceDeviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListFailoverTargetsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FailoverTarget&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="sourceDeviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ListFailoverTargetsRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-292">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceDeviceName">
            <span data-ttu-id="7755e-293">フェールオーバーの実行対象となるソース デバイスの名前。</span><span class="sxs-lookup"><span data-stu-id="7755e-293">The source device name on which failover is performed.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-294">フェールオーバーするボリューム コンテナーの一覧を含む ListFailoverTargetsRequest です。</span><span class="sxs-lookup"><span data-stu-id="7755e-294">ListFailoverTargetsRequest containing the list of volume containers to be failed over.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-295">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-295">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-296">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-296">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-297">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-297">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-298">ソース デバイスからはフェールオーバーするボリューム コンテナーの一覧を指定するには、このメソッドは、そのリソースの下のすべてのデバイスのフェールオーバー ターゲットとしての対象となる結果を返します。</span><span class="sxs-lookup"><span data-stu-id="7755e-298">Given a list of volume containers to be failed over from a source device, this method returns the eligibility result, as a failover target, for all devices under that resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinition (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-299">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-299">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-300">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-300">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-301">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-301">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-302">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-302">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-303">指定したデバイスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="7755e-303">Gets the metric definitions for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-304">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-304">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-305">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-305">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-306">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-306">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-307">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-307">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-308">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-308">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-309">指定したデバイスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="7755e-309">Gets the metric definitions for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IDevicesOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-310">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7755e-311">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7755e-311">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-312">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-312">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-313">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-313">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-314">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-314">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-315">指定したデバイスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7755e-315">Gets the metrics for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ListMetricsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-316">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-316">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7755e-317">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7755e-317">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-318">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-318">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-319">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-319">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-320">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-320">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-321">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-322">指定したデバイスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7755e-322">Gets the metrics for the specified device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanForUpdates">
      <MemberSignature Language="C#" Value="public static void ScanForUpdates (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ScanForUpdates(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdates(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ScanForUpdates (operations As IDevicesOperations, deviceName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member ScanForUpdates : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdates (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-323">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-323">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-324">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-324">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-325">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-325">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-326">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-326">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-327">デバイスの更新プログラムをスキャンします。</span><span class="sxs-lookup"><span data-stu-id="7755e-327">Scans for updates on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanForUpdatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ScanForUpdatesAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ScanForUpdatesAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdatesAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ScanForUpdatesAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.ScanForUpdatesAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;ScanForUpdatesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-328">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-328">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-329">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-329">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-330">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-330">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-331">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-331">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-332">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-332">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-333">デバイスの更新プログラムをスキャンします。</span><span class="sxs-lookup"><span data-stu-id="7755e-333">Scans for updates on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Device Update (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Device Update(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Update(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IDevicesOperations, deviceName As String, parameters As DevicePatch, resourceGroupName As String, managerName As String) As Device" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.Update (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Device</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-334">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-334">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-335">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-335">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-336">デバイスの修正プログラム表現。</span><span class="sxs-lookup"><span data-stu-id="7755e-336">Patch representation of the device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-337">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-337">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-338">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-338">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-339">デバイスを修正します。</span><span class="sxs-lookup"><span data-stu-id="7755e-339">Patches the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; UpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt; UpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions.UpdateAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.DevicesOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IDevicesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DevicePatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7755e-340">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7755e-340">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="7755e-341">デバイス名</span><span class="sxs-lookup"><span data-stu-id="7755e-341">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7755e-342">デバイスの修正プログラム表現。</span><span class="sxs-lookup"><span data-stu-id="7755e-342">Patch representation of the device.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7755e-343">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="7755e-343">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="7755e-344">管理者名</span><span class="sxs-lookup"><span data-stu-id="7755e-344">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7755e-345">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7755e-345">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7755e-346">デバイスを修正します。</span><span class="sxs-lookup"><span data-stu-id="7755e-346">Patches the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>