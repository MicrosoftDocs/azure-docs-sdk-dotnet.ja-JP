<Type Name="VolumesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VolumesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VolumesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VolumesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VolumesOperationsExtensions = class" />
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
            <span data-ttu-id="3aaa7-101">VolumesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-101">Extension methods for VolumesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, parameters As Volume, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-103">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-103">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-104">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-104">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-105">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-105">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3aaa7-106">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-106">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-107">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-108">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-109">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-109">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-111">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-111">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-112">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-112">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-113">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-113">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3aaa7-114">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-114">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-118">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-118">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDelete (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-120">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-120">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-121">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-121">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-122">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-122">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-123">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-124">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-124">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-125">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-125">Deletes the volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDeleteAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-126">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-127">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-127">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-128">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-128">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-129">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-129">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-130">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-130">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-131">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-131">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-133">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-133">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, parameters As Volume, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdate (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-134">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-135">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-135">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-136">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-136">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-137">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-137">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3aaa7-138">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-138">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-140">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-141">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-141">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-142">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-143">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-143">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-144">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-144">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-145">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-145">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3aaa7-146">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-146">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-148">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-150">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-150">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Delete (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-152">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-152">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-153">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-153">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-154">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-154">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-155">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-156">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-156">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-157">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-157">Deletes the volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.DeleteAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-159">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-159">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-160">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-160">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-161">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-161">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-162">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-163">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-163">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-165">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-165">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume Get (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume Get(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Get (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-166">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-167">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-167">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-168">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-168">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-169">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-169">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-170">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-170">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-171">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-171">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-172">指定したボリューム名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-172">Returns the properties of the specified volume name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.GetAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-173">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-174">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-174">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-175">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-175">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-176">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-176">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-177">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-178">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-180">指定したボリューム名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-180">Returns the properties of the specified volume name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IVolumesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Volume)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-181">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-182">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-182">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-183">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-183">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-184">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-184">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-185">デバイスのすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-185">Retrieves all the volumes in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListByDeviceAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-186">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-187">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-187">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-188">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-188">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-189">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-189">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-191">デバイスのすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-191">Retrieves all the volumes in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByVolumeContainer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByVolumeContainer (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByVolumeContainer(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainer(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByVolumeContainer (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Volume)" />
      <MemberSignature Language="F#" Value="static member ListByVolumeContainer : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainer (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-192">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-193">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-193">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-194">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-194">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-195">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-195">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-196">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-196">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-197">ボリューム コンテナー内のすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-197">Retrieves all the volumes in a volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByVolumeContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByVolumeContainerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByVolumeContainerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainerAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByVolumeContainerAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainerAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListByVolumeContainerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-198">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-199">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-199">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-200">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-200">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-201">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-201">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-202">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-202">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-204">ボリューム コンテナー内のすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-204">Retrieves all the volumes in a volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinition (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-205">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-206">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-206">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-207">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-207">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-208">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-208">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-209">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-209">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-210">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-210">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-211">指定したボリュームのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-211">Gets the metric definitions for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-212">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-213">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-213">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-214">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-214">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-215">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-215">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-216">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-216">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-217">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-217">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-219">指定したボリュームのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-219">Gets the metric definitions for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IVolumesOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-220">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="3aaa7-221">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-221">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-222">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-222">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-223">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-223">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-224">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-224">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-225">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-225">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-226">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-226">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-227">指定したボリュームのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-227">Gets the metrics for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListMetricsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3aaa7-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-228">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="3aaa7-229">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-229">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3aaa7-230">デバイス名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-230">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="3aaa7-231">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-231">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="3aaa7-232">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-232">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3aaa7-233">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-233">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3aaa7-234">管理者名</span><span class="sxs-lookup"><span data-stu-id="3aaa7-234">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3aaa7-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3aaa7-236">指定したボリュームのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3aaa7-236">Gets the metrics for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>