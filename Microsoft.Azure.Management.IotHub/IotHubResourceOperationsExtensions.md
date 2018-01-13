<Type Name="IotHubResourceOperationsExtensions" FullName="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IotHubResourceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IotHubResourceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IotHubResourceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IotHubResourceOperationsExtensions = class" />
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
            <span data-ttu-id="cbf80-101">IotHubResourceOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="cbf80-101">Extension methods for IotHubResourceOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription BeginCreateOrUpdate (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription BeginCreateOrUpdate(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-103">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-103">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-104">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-104">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="cbf80-105">IoT ハブ メタデータとセキュリティのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="cbf80-105">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf80-106">IoT Hub の ETag。</span><span class="sxs-lookup"><span data-stu-id="cbf80-106">ETag of the IoT Hub.</span></span> <span data-ttu-id="cbf80-107">新しい IoT Hub を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf80-107">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="cbf80-108">既存の IoT Hub を更新する必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-108">Required to update an existing IoT Hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-109">作成または IoT hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-109">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-110">作成または Iot hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-110">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="cbf80-111">IoT hub のメタデータとセキュリティのメタデータを取得し、それらを IoT hub を更新する新しいボディで変更された値を持つ結合するプロパティを変更する一般的なパターンです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-111">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-113">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-113">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-114">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-114">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="cbf80-115">IoT ハブ メタデータとセキュリティのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="cbf80-115">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf80-116">IoT Hub の ETag。</span><span class="sxs-lookup"><span data-stu-id="cbf80-116">ETag of the IoT Hub.</span></span> <span data-ttu-id="cbf80-117">新しい IoT Hub を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf80-117">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="cbf80-118">既存の IoT Hub を更新する必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-118">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-120">作成または IoT hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-120">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-121">作成または Iot hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-121">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="cbf80-122">IoT hub のメタデータとセキュリティのメタデータを取得し、それらを IoT hub を更新する新しいボディで変更された値を持つ結合するプロパティを変更する一般的なパターンです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-122">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static object BeginDelete (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object BeginDelete(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDelete(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As Object" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDelete (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-124">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-124">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-125">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-125">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-126">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-126">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-127">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-127">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; BeginDeleteAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; BeginDeleteAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;BeginDeleteAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-129">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-129">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-130">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-130">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-132">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-132">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-133">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-133">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo CheckNameAvailability (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo CheckNameAvailability(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, class Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,Microsoft.Azure.Management.IotHub.Models.OperationInputs)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * Microsoft.Azure.Management.IotHub.Models.OperationInputs -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailability (operations, operationInputs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="operationInputs" Type="Microsoft.Azure.Management.IotHub.Models.OperationInputs" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-134">The operations group for this extension method.</span></span>
            </param>
        <param name="operationInputs">
            <span data-ttu-id="cbf80-135">OperationInputs 構造を確認する IoT hub の名前に、name パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-135">Set the name parameter in the OperationInputs structure to the name of the IoT hub to check.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-136">IoT ハブ名があるかを確認してください。</span><span class="sxs-lookup"><span data-stu-id="cbf80-136">Check if an IoT hub name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-137">IoT ハブ名があるかを確認してください。</span><span class="sxs-lookup"><span data-stu-id="cbf80-137">Check if an IoT hub name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, class Microsoft.Azure.Management.IotHub.Models.OperationInputs operationInputs, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,Microsoft.Azure.Management.IotHub.Models.OperationInputs,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * Microsoft.Azure.Management.IotHub.Models.OperationInputs * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CheckNameAvailabilityAsync (operations, operationInputs, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="operationInputs" Type="Microsoft.Azure.Management.IotHub.Models.OperationInputs" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-138">The operations group for this extension method.</span></span>
            </param>
        <param name="operationInputs">
            <span data-ttu-id="cbf80-139">OperationInputs 構造を確認する IoT hub の名前に、name パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-139">Set the name parameter in the OperationInputs structure to the name of the IoT hub to check.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-141">IoT ハブ名があるかを確認してください。</span><span class="sxs-lookup"><span data-stu-id="cbf80-141">Check if an IoT hub name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-142">IoT ハブ名があるかを確認してください。</span><span class="sxs-lookup"><span data-stu-id="cbf80-142">Check if an IoT hub name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo CreateEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo CreateEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String) As EventHubConsumerGroupInfo" />
      <MemberSignature Language="F#" Value="static member CreateEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-144">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-144">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-145">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-145">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-146">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-146">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-147">追加するコンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-147">The name of the consumer group to add.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-148">IoT hub でイベント ハブと互換性のあるエンドポイントにコンシューマー グループを追加します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-148">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-149">IoT hub でイベント ハブと互換性のあるエンドポイントにコンシューマー グループを追加します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-149">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; CreateEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; CreateEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CreateEventHubConsumerGroupAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-151">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-151">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-152">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-152">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-153">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-153">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-154">追加するコンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-154">The name of the consumer group to add.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-156">IoT hub でイベント ハブと互換性のあるエンドポイントにコンシューマー グループを追加します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-156">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-157">IoT hub でイベント ハブと互換性のあるエンドポイントにコンシューマー グループを追加します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-157">Add a consumer group to an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription CreateOrUpdate (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription CreateOrUpdate(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-159">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-159">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-160">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-160">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="cbf80-161">IoT ハブ メタデータとセキュリティのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="cbf80-161">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf80-162">IoT Hub の ETag。</span><span class="sxs-lookup"><span data-stu-id="cbf80-162">ETag of the IoT Hub.</span></span> <span data-ttu-id="cbf80-163">新しい IoT Hub を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf80-163">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="cbf80-164">既存の IoT Hub を更新する必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-164">Required to update an existing IoT Hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-165">作成または IoT hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-165">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-166">作成または Iot hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-166">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="cbf80-167">IoT hub のメタデータとセキュリティのメタデータを取得し、それらを IoT hub を更新する新しいボディで変更された値を持つ結合するプロパティを変更する一般的なパターンです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-167">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.IotHubDescription iotHubDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.IotHubDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.IotHubDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, iotHubDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="iotHubDescription" Type="Microsoft.Azure.Management.IotHub.Models.IotHubDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-169">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-169">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-170">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-170">The name of the IoT hub.</span></span>
            </param>
        <param name="iotHubDescription">
            <span data-ttu-id="cbf80-171">IoT ハブ メタデータとセキュリティのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="cbf80-171">The IoT hub metadata and security metadata.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf80-172">IoT Hub の ETag。</span><span class="sxs-lookup"><span data-stu-id="cbf80-172">ETag of the IoT Hub.</span></span> <span data-ttu-id="cbf80-173">新しい IoT Hub を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf80-173">Do not specify for creating a brand new IoT Hub.</span></span>
            <span data-ttu-id="cbf80-174">既存の IoT Hub を更新する必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-174">Required to update an existing IoT Hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-176">作成または IoT hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-176">Create or update the metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-177">作成または Iot hub のメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-177">Create or update the metadata of an Iot hub.</span></span> <span data-ttu-id="cbf80-178">IoT hub のメタデータとセキュリティのメタデータを取得し、それらを IoT hub を更新する新しいボディで変更された値を持つ結合するプロパティを変更する一般的なパターンです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-178">The usual pattern to modify a property is to retrieve the IoT hub metadata and security metadata, and then combine them with the modified values in a new body to update the IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static object Delete (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object Delete(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Delete(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As Object" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Delete (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-180">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-180">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-181">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-181">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-182">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-182">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-183">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-183">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-185">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-185">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-186">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-186">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-188">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-188">Delete an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-189">IoT hub を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-189">Delete an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static void DeleteEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member DeleteEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-191">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-191">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-192">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-192">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-193">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-193">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-194">削除するコンシューマー グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-194">The name of the consumer group to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-195">IoT hub にイベント ハブと互換性のあるエンドポイントからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-195">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="cbf80-196">IoT hub にイベント ハブと互換性のあるエンドポイントからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-196">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.DeleteEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;DeleteEventHubConsumerGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-198">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-198">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-199">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-199">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-200">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-200">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-201">削除するコンシューマー グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-201">The name of the consumer group to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-203">IoT hub にイベント ハブと互換性のあるエンドポイントからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-203">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-204">IoT hub にイベント ハブと互換性のあるエンドポイントからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-204">Delete a consumer group from an Event Hub-compatible endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevices">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse ExportDevices (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse ExportDevices(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevices(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportDevices (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, exportDevicesParameters As ExportDevicesRequest) As JobResponse" />
      <MemberSignature Language="F#" Value="static member ExportDevices : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevices (operations, resourceGroupName, resourceName, exportDevicesParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="exportDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-206">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-206">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-207">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-207">The name of the IoT hub.</span></span>
            </param>
        <param name="exportDevicesParameters">
            <span data-ttu-id="cbf80-208">デバイスのエクスポート操作を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-208">The parameters that specify the export devices operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-209">IoT hub id レジストリ内のすべてのデバイス id を Azure Storage blob コンテナーにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cbf80-209">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="cbf80-210">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-210">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-211">IoT hub id レジストリ内のすべてのデバイス id を Azure Storage blob コンテナーにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cbf80-211">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="cbf80-212">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-212">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ExportDevicesAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ExportDevicesAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest exportDevicesParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevicesAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportDevicesAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ExportDevicesAsync (operations, resourceGroupName, resourceName, exportDevicesParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ExportDevicesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="exportDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-214">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-214">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-215">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-215">The name of the IoT hub.</span></span>
            </param>
        <param name="exportDevicesParameters">
            <span data-ttu-id="cbf80-216">デバイスのエクスポート操作を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-216">The parameters that specify the export devices operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-218">IoT hub id レジストリ内のすべてのデバイス id を Azure Storage blob コンテナーにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cbf80-218">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="cbf80-219">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-219">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-220">IoT hub id レジストリ内のすべてのデバイス id を Azure Storage blob コンテナーにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cbf80-220">Exports all the device identities in the IoT hub identity registry to an Azure Storage blob container.</span></span> <span data-ttu-id="cbf80-221">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-221">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.IotHubDescription Get (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.IotHubDescription Get(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Get(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IotHubDescription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubDescription" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.Get (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IotHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-223">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-223">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-224">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-224">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-225">IoT hub のセキュリティ以外の関連するメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-225">Get the non-security related metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-226">IoT hub のセキュリティ以外の関連するメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-226">Get the non-security related metadata of an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; GetAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; GetAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-228">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-228">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-229">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-229">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-231">IoT hub のセキュリティ以外の関連するメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-231">Get the non-security related metadata of an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-232">IoT hub のセキュリティ以外の関連するメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-232">Get the non-security related metadata of an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubConsumerGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo GetEventHubConsumerGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo GetEventHubConsumerGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetEventHubConsumerGroup (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String, name As String) As EventHubConsumerGroupInfo" />
      <MemberSignature Language="F#" Value="static member GetEventHubConsumerGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroup (operations, resourceGroupName, resourceName, eventHubEndpointName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-234">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-234">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-235">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-235">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-236">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-236">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-237">取得するコンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-237">The name of the consumer group to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-238">IoT hub のイベント ハブと互換性のあるデバイスとクラウド エンドポイントからのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-238">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-239">IoT hub のイベント ハブと互換性のあるデバイスとクラウド エンドポイントからのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-239">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; GetEventHubConsumerGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt; GetEventHubConsumerGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetEventHubConsumerGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetEventHubConsumerGroupAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetEventHubConsumerGroupAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.EventHubConsumerGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-240">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-241">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-241">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-242">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-242">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-243">IoT hub にイベント ハブと互換性のあるエンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-243">The name of the Event Hub-compatible endpoint in the IoT hub.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="cbf80-244">取得するコンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-244">The name of the consumer group to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-246">IoT hub のイベント ハブと互換性のあるデバイスとクラウド エンドポイントからのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-246">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-247">IoT hub のイベント ハブと互換性のあるデバイスとクラウド エンドポイントからのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-247">Get a consumer group from the Event Hub-compatible device-to-cloud endpoint for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse GetJob (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse GetJob(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJob(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetJob (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, jobId As String) As JobResponse" />
      <MemberSignature Language="F#" Value="static member GetJob : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJob (operations, resourceGroupName, resourceName, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-249">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-249">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-250">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-250">The name of the IoT hub.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbf80-251">ジョブの識別子です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-251">The job identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-252">IoT hub からジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-252">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="cbf80-253">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-253">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-254">IoT hub からジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-254">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="cbf80-255">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-255">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; GetJobAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; GetJobAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJobAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetJobAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetJobAsync (operations, resourceGroupName, resourceName, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetJobAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-257">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-257">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-258">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-258">The name of the IoT hub.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbf80-259">ジョブの識別子です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-259">The job identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-260">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-261">IoT hub からジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-261">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="cbf80-262">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-262">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-263">IoT hub からジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-263">Get the details of a job from an IoT hub.</span></span> <span data-ttu-id="cbf80-264">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-264">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysForKeyName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule GetKeysForKeyName (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule GetKeysForKeyName(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyName(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetKeysForKeyName (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, keyName As String) As SharedAccessSignatureAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetKeysForKeyName : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyName (operations, resourceGroupName, resourceName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-266">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-266">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-267">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-267">The name of the IoT hub.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="cbf80-268">共有アクセス ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-268">The name of the shared access policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-269">IoT hub から名前で共有アクセス ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-269">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="cbf80-270">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-270">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-271">IoT hub から名前で共有アクセス ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-271">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="cbf80-272">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-272">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysForKeyNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; GetKeysForKeyNameAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; GetKeysForKeyNameAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyNameAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysForKeyNameAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetKeysForKeyNameAsync (operations, resourceGroupName, resourceName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetKeysForKeyNameAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-274">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-274">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-275">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-275">The name of the IoT hub.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="cbf80-276">共有アクセス ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-276">The name of the shared access policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-277">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-278">IoT hub から名前で共有アクセス ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-278">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="cbf80-279">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-279">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-280">IoT hub から名前で共有アクセス ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-280">Get a shared access policy by name from an IoT hub.</span></span> <span data-ttu-id="cbf80-281">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-281">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetrics (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetrics(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetrics(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetQuotaMetrics (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of IotHubQuotaMetricInfo)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetrics : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetrics (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-282">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-282">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-283">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-283">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-284">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-284">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-285">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-285">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-286">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-286">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetQuotaMetricsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-287">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-288">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-288">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-289">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-289">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-290">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-291">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-291">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-292">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-292">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetricsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt; GetQuotaMetricsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetQuotaMetricsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubQuotaMetricInfo)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-293">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-293">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-294">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-294">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-295">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-295">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-296">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-296">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQuotaMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt; GetQuotaMetricsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotaMetricsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetQuotaMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetQuotaMetricsNextAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubQuotaMetricInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-297">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-297">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-298">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-298">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-300">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-300">Get the quota metrics for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-301">IoT hub のクォータ メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-301">Get the quota metrics for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.RegistryStatistics GetStats (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.RegistryStatistics GetStats(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStats(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStats (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As RegistryStatistics" />
      <MemberSignature Language="F#" Value="static member GetStats : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.RegistryStatistics" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStats (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.RegistryStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-302">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-302">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-303">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-303">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-304">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-304">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-305">IoT hub から統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-305">Get the statistics from an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-306">IoT hub から統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-306">Get the statistics from an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt; GetStatsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt; GetStatsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetStatsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetStatsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-307">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-308">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-308">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-309">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-309">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-311">IoT hub から統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-311">Get the statistics from an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-312">IoT hub から統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-312">Get the statistics from an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkus (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkus(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkus(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetValidSkus (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of IotHubSkuDescription)" />
      <MemberSignature Language="F#" Value="static member GetValidSkus : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkus (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-313">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-314">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-314">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-315">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-315">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-316">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-316">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-317">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-317">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetValidSkusAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-318">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-318">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-319">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-319">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-320">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-320">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-321">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-322">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-322">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-323">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-323">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkusNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt; GetValidSkusNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetValidSkusNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubSkuDescription)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-324">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-324">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-325">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-325">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-326">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-326">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-327">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-327">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValidSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt; GetValidSkusNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetValidSkusNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.GetValidSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;GetValidSkusNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubSkuDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-328">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-328">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-329">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-329">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-330">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-331">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-331">Get the list of valid SKUs for an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-332">IoT hub の有効な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-332">Get the list of valid SKUs for an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevices">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.JobResponse ImportDevices (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.JobResponse ImportDevices(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevices(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ImportDevices (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, importDevicesParameters As ImportDevicesRequest) As JobResponse" />
      <MemberSignature Language="F#" Value="static member ImportDevices : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest -&gt; Microsoft.Azure.Management.IotHub.Models.JobResponse" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevices (operations, resourceGroupName, resourceName, importDevicesParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="importDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-333">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-333">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-334">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-334">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-335">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-335">The name of the IoT hub.</span></span>
            </param>
        <param name="importDevicesParameters">
            <span data-ttu-id="cbf80-336">デバイスのインポート操作を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-336">The parameters that specify the import devices operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-337">インポート、更新、または blob から IoT ハブ id レジストリ内のデバイス id を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-337">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="cbf80-338">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-338">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-339">インポート、更新、または blob から IoT ハブ id レジストリ内のデバイス id を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-339">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="cbf80-340">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-340">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ImportDevicesAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ImportDevicesAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest importDevicesParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevicesAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportDevicesAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ImportDevicesAsync (operations, resourceGroupName, resourceName, importDevicesParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ImportDevicesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="importDevicesParameters" Type="Microsoft.Azure.Management.IotHub.Models.ImportDevicesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-341">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-341">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-342">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-342">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-343">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-343">The name of the IoT hub.</span></span>
            </param>
        <param name="importDevicesParameters">
            <span data-ttu-id="cbf80-344">デバイスのインポート操作を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-344">The parameters that specify the import devices operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-345">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-345">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-346">インポート、更新、または blob から IoT ハブ id レジストリ内のデバイス id を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-346">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="cbf80-347">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-347">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-348">インポート、更新、または blob から IoT ハブ id レジストリ内のデバイス id を削除します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-348">Import, update, or delete device identities in the IoT hub identity registry from a blob.</span></span> <span data-ttu-id="cbf80-349">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-349">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroup (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroup(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IIotHubResourceOperations, resourceGroupName As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-350">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-350">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-351">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-351">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-352">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-352">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-353">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-353">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-354">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-354">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-355">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-355">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-356">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-356">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-357">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-357">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-358">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-358">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-359">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-359">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-360">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-360">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-361">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-361">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-362">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-362">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-363">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-363">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-364">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-364">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-365">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-365">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-366">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-366">Get all the IoT hubs in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-367">リソース グループ内のすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-367">Get all the IoT hubs in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscription">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscription (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscription(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscription(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscription (operations As IIotHubResourceOperations) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListBySubscription : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-368">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-368">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-369">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-369">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-370">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-370">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-371">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-371">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-372">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-372">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-373">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-373">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-374">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-374">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscriptionNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt; ListBySubscriptionNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of IotHubDescription)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-375">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-375">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-376">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-376">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-377">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-377">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-378">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-378">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt; ListBySubscriptionNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListBySubscriptionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListBySubscriptionNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.IotHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-379">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-379">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-380">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-380">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-381">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-382">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-382">Get all the IoT hubs in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-383">サブスクリプションのすべての IoT hub を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-383">Get all the IoT hubs in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListEventHubConsumerGroups (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListEventHubConsumerGroups(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroups(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventHubConsumerGroups (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String, eventHubEndpointName As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroups : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroups (operations, resourceGroupName, resourceName, eventHubEndpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-384">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-384">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-385">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-385">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-386">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-386">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-387">イベント ハブと互換性のあるエンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-387">The name of the Event Hub-compatible endpoint.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-388">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-388">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-389">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-389">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListEventHubConsumerGroupsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListEventHubConsumerGroupsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, string eventHubEndpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsAsync (operations, resourceGroupName, resourceName, eventHubEndpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListEventHubConsumerGroupsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="eventHubEndpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-390">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-390">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-391">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-391">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-392">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-392">The name of the IoT hub.</span></span>
            </param>
        <param name="eventHubEndpointName">
            <span data-ttu-id="cbf80-393">イベント ハブと互換性のあるエンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-393">The name of the Event Hub-compatible endpoint.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-394">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-395">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-395">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-396">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-396">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListEventHubConsumerGroupsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListEventHubConsumerGroupsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventHubConsumerGroupsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-397">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-397">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-398">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-398">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-399">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-399">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-400">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-400">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventHubConsumerGroupsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListEventHubConsumerGroupsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListEventHubConsumerGroupsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventHubConsumerGroupsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListEventHubConsumerGroupsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListEventHubConsumerGroupsNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-401">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-401">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-402">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-402">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-403">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-403">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-404">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-404">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-405">IoT hub にイベント ハブと互換性のあるデバイスとクラウドのエンドポイントでは、コンシューマー グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-405">Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobs (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobs(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobs(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobs (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of JobResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobs : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobs (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-406">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-406">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-407">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-407">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-408">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-408">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-409">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-409">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-410">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-410">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-411">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-411">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-412">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-412">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListJobsAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListJobsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-413">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-413">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-414">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-414">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-415">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-415">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-416">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-416">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-417">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-417">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-418">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-418">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-419">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-419">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-420">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-420">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobsNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt; ListJobsNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListJobsNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of JobResponse)" />
      <MemberSignature Language="F#" Value="static member ListJobsNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-421">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-421">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-422">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-422">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-423">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-423">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-424">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-424">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-425">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-425">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-426">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-426">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt; ListJobsNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListJobsNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListJobsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListJobsNextAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.JobResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-427">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-427">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-428">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-428">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-429">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-430">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-430">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-431">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-431">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-432">IoT hub でのすべてのジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-432">Get a list of all the jobs in an IoT hub.</span></span> <span data-ttu-id="cbf80-433">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-433">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeys (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeys(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeys(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IIotHubResourceOperations, resourceGroupName As String, resourceName As String) As IPage(Of SharedAccessSignatureAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeys (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-434">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-434">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-435">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-435">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-436">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-436">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-437">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-437">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-438">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-438">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-439">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-439">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-440">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-440">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListKeysAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-441">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-441">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf80-442">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-442">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf80-443">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf80-443">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-444">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-445">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-445">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-446">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-446">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-447">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-447">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-448">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-448">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeysNext (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; ListKeysNext(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNext(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeysNext (operations As IIotHubResourceOperations, nextPageLink As String) As IPage(Of SharedAccessSignatureAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListKeysNext : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-449">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-449">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-450">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-450">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-451">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-451">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-452">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-452">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-453">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-453">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-454">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-454">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysNextAsync (this Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt; ListKeysNextAsync(class Microsoft.Azure.Management.IotHub.IIotHubResourceOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNextAsync(Microsoft.Azure.Management.IotHub.IIotHubResourceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysNextAsync : Microsoft.Azure.Management.IotHub.IIotHubResourceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions.ListKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.IotHubResourceOperationsExtensions/&lt;ListKeysNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.IIotHubResourceOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf80-455">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf80-455">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="cbf80-456">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-456">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf80-457">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf80-457">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf80-458">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-458">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-459">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-459">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf80-460">IoT hub のセキュリティ メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf80-460">Get the security metadata for an IoT hub.</span></span> <span data-ttu-id="cbf80-461">詳細についてを参照してください: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security です。</span><span class="sxs-lookup"><span data-stu-id="cbf80-461">For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>