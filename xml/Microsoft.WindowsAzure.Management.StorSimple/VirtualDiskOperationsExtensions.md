<Type Name="VirtualDiskOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDiskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDiskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDiskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDiskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="59efb-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="59efb-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreating (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-102">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-103">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-103">Required.</span></span> <span data-ttu-id="59efb-104">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-104">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-105">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-105">Required.</span></span> <span data-ttu-id="59efb-106">仮想ディスクの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-106">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-107">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-107">Required.</span></span> <span data-ttu-id="59efb-108">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-109">作成するボリュームの開始の操作では、新しいボリュームを作成します。</span><span class="sxs-lookup"><span data-stu-id="59efb-109">The Begin Creating Volume operation creates a new volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-110">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginCreatingAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-111">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-112">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-112">Required.</span></span> <span data-ttu-id="59efb-113">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-113">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-114">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-114">Required.</span></span> <span data-ttu-id="59efb-115">仮想ディスクの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-115">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-116">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-116">Required.</span></span> <span data-ttu-id="59efb-117">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-118">作成するボリュームの開始の操作では、新しいボリュームを作成します。</span><span class="sxs-lookup"><span data-stu-id="59efb-118">The Begin Creating Volume operation creates a new volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-119">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeleting (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-120">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-121">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-121">Required.</span></span> <span data-ttu-id="59efb-122">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-122">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-123">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-123">Required.</span></span> <span data-ttu-id="59efb-124">削除する仮想ディスクのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="59efb-124">Instance id of the virtual disk to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-125">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-125">Required.</span></span> <span data-ttu-id="59efb-126">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-127">削除してもボリュームの開始操作には、指定したボリュームが削除されます。</span><span class="sxs-lookup"><span data-stu-id="59efb-127">The Begin Deleteing Volume operation deletes the specified volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-128">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginDeletingAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-129">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-130">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-130">Required.</span></span> <span data-ttu-id="59efb-131">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-131">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-132">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-132">Required.</span></span> <span data-ttu-id="59efb-133">削除する仮想ディスクのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="59efb-133">Instance id of the virtual disk to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-134">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-134">Required.</span></span> <span data-ttu-id="59efb-135">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-136">削除してもボリュームの開始操作には、指定したボリュームが削除されます。</span><span class="sxs-lookup"><span data-stu-id="59efb-136">The Begin Deleteing Volume operation deletes the specified volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-137">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdating(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdating : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdating (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-138">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-139">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-139">Required.</span></span> <span data-ttu-id="59efb-140">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-140">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-141">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-141">Required.</span></span> <span data-ttu-id="59efb-142">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-142">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-143">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-143">Required.</span></span> <span data-ttu-id="59efb-144">仮想ディスクの更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-144">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-145">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-145">Required.</span></span> <span data-ttu-id="59efb-146">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-146">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-147">ボリュームの操作の更新を開始では、既存のボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="59efb-147">The Begin updating Volume operation updates an existing volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-148">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-148">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.BeginUpdatingAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-149">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-149">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-150">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-150">Required.</span></span> <span data-ttu-id="59efb-151">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-151">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-152">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-152">Required.</span></span> <span data-ttu-id="59efb-153">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-153">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-154">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-154">Required.</span></span> <span data-ttu-id="59efb-155">仮想ディスクの更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-155">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-156">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-156">Required.</span></span> <span data-ttu-id="59efb-157">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-157">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="59efb-158">ボリュームの操作の更新を開始では、既存のボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="59efb-158">The Begin updating Volume operation updates an existing volume.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="59efb-159">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="59efb-159">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Create (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-160">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-160">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-161">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-161">Required.</span></span> <span data-ttu-id="59efb-162">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-162">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-163">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-163">Required.</span></span> <span data-ttu-id="59efb-164">仮想ディスクの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-164">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-165">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-165">Required.</span></span> <span data-ttu-id="59efb-166">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-167">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-167">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.CreateAsync (operations, deviceId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-168">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-169">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-169">Required.</span></span> <span data-ttu-id="59efb-170">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-170">device id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-171">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-171">Required.</span></span> <span data-ttu-id="59efb-172">仮想ディスクの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-172">Parameters supplied to the Create virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-173">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-173">Required.</span></span> <span data-ttu-id="59efb-174">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-174">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-175">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-175">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Delete (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-176">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-176">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-177">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-177">Required.</span></span> <span data-ttu-id="59efb-178">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-178">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-179">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-179">Required.</span></span> <span data-ttu-id="59efb-180">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-180">disk id</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-181">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-181">Required.</span></span> <span data-ttu-id="59efb-182">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-182">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-183">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-183">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.DeleteAsync (operations, deviceId, diskId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-184">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-185">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-185">Required.</span></span> <span data-ttu-id="59efb-186">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-186">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-187">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-187">Required.</span></span> <span data-ttu-id="59efb-188">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-188">disk id</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-189">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-189">Required.</span></span> <span data-ttu-id="59efb-190">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-190">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-191">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-191">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse GetByName(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByName : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByName (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-192">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-192">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-193">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-193">Optional.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="59efb-194">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-194">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-195">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-195">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-196">仮想ディスクの get 応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="59efb-196">The response model for the get of virtual disk.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt; GetByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.GetByNameAsync (operations, deviceId, diskName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-197">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-197">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-198">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-198">Optional.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="59efb-199">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-199">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-200">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-200">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-201">仮想ディスクの get 応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="59efb-201">The response model for the get of virtual disk.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.List (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-202">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-202">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-203">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-203">Optional.</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="59efb-204">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-204">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-205">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-205">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-206">指定されたデータのコンテナー用の仮想ディスクの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="59efb-206">The response model for the list of virtual disks for a given data container.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.ListAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-207">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-207">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-208">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-208">Optional.</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="59efb-209">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-209">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-210">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59efb-210">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-211">指定されたデータのコンテナー用の仮想ディスクの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="59efb-211">The response model for the list of virtual disks for a given data container.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.Update (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-212">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-212">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-213">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-213">Required.</span></span> <span data-ttu-id="59efb-214">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-214">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-215">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-215">Required.</span></span> <span data-ttu-id="59efb-216">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-216">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-217">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-217">Required.</span></span> <span data-ttu-id="59efb-218">仮想ディスクの更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-218">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-219">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-219">Required.</span></span> <span data-ttu-id="59efb-220">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-220">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-221">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-221">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations operations, string deviceId, string diskId, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk diskDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDiskOperationsExtensions.UpdateAsync (operations, deviceId, diskId, diskDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="diskId" Type="System.String" />
        <Parameter Name="diskDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="59efb-222">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="59efb-222">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="59efb-223">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-223">Required.</span></span> <span data-ttu-id="59efb-224">デバイス id</span><span class="sxs-lookup"><span data-stu-id="59efb-224">device id</span></span>
            </param>
        <param name="diskId">
            <span data-ttu-id="59efb-225">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-225">Required.</span></span> <span data-ttu-id="59efb-226">ディスク id</span><span class="sxs-lookup"><span data-stu-id="59efb-226">disk id</span></span>
            </param>
        <param name="diskDetails">
            <span data-ttu-id="59efb-227">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-227">Required.</span></span> <span data-ttu-id="59efb-228">仮想ディスクの更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="59efb-228">Parameters supplied to the update virtual disk operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="59efb-229">必須。</span><span class="sxs-lookup"><span data-stu-id="59efb-229">Required.</span></span> <span data-ttu-id="59efb-230">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="59efb-230">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="59efb-231">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="59efb-231">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>