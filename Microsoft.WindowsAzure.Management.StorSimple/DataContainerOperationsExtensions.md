<Type Name="DataContainerOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataContainerOperationsExtensions = class" />
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
            <span data-ttu-id="26432-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="26432-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreating (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-102">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-103">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-103">Required.</span></span> <span data-ttu-id="26432-104">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-104">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="26432-105">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-105">Required.</span></span> <span data-ttu-id="26432-106">パラメーターは、作成するボリューム コンテナーの開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="26432-106">Parameters supplied to the Begin Creating Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-107">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-107">Required.</span></span> <span data-ttu-id="26432-108">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="26432-109">作成するボリューム コンテナーの開始操作は、新しいボリューム コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="26432-109">The Begin Creating Volume Container operation creates a new volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="26432-110">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="26432-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginCreatingAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-111">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-112">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-112">Required.</span></span> <span data-ttu-id="26432-113">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-113">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="26432-114">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-114">Required.</span></span> <span data-ttu-id="26432-115">パラメーターは、作成するボリューム コンテナーの開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="26432-115">Parameters supplied to the Begin Creating Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-116">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-116">Required.</span></span> <span data-ttu-id="26432-117">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="26432-118">作成するボリューム コンテナーの開始操作は、新しいボリューム コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="26432-118">The Begin Creating Volume Container operation creates a new volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="26432-119">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="26432-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeleting (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-120">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-121">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-121">Required.</span></span> <span data-ttu-id="26432-122">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-122">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="26432-123">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-123">Required.</span></span> <span data-ttu-id="26432-124">削除する必要があるデータ コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="26432-124">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-125">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-125">Required.</span></span> <span data-ttu-id="26432-126">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="26432-127">削除するボリューム コンテナーの開始操作には、指定したボリューム コンテナーが削除されます。</span><span class="sxs-lookup"><span data-stu-id="26432-127">The Begin Deleting Volume Container operation deletes the specified volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="26432-128">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="26432-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.BeginDeletingAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-129">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-130">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-130">Required.</span></span> <span data-ttu-id="26432-131">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-131">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="26432-132">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-132">Required.</span></span> <span data-ttu-id="26432-133">削除する必要があるデータ コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="26432-133">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-134">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-134">Required.</span></span> <span data-ttu-id="26432-135">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="26432-136">削除するボリューム コンテナーの開始操作には、指定したボリューム コンテナーが削除されます。</span><span class="sxs-lookup"><span data-stu-id="26432-136">The Begin Deleting Volume Container operation deletes the specified volume container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="26432-137">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="26432-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Create (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-138">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-139">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-139">Required.</span></span> <span data-ttu-id="26432-140">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-140">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="26432-141">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-141">Required.</span></span> <span data-ttu-id="26432-142">パラメーターは、ボリューム コンテナーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="26432-142">Parameters supplied to the Create Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-143">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-143">Required.</span></span> <span data-ttu-id="26432-144">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-144">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-145">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="26432-145">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest containerDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.CreateAsync (operations, deviceId, containerDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="containerDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-146">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-146">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-147">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-147">Required.</span></span> <span data-ttu-id="26432-148">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-148">device id</span></span>
            </param>
        <param name="containerDetails">
            <span data-ttu-id="26432-149">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-149">Required.</span></span> <span data-ttu-id="26432-150">パラメーターは、ボリューム コンテナーの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="26432-150">Parameters supplied to the Create Volume Container operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-151">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-151">Required.</span></span> <span data-ttu-id="26432-152">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-152">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-153">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="26432-153">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Delete (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-154">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-154">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-155">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-155">Required.</span></span> <span data-ttu-id="26432-156">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-156">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="26432-157">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-157">Required.</span></span> <span data-ttu-id="26432-158">削除する必要があるデータ コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="26432-158">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-159">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-159">Required.</span></span> <span data-ttu-id="26432-160">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-160">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-161">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="26432-161">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.DeleteAsync (operations, deviceId, dataContainerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-162">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-162">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-163">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-163">Required.</span></span> <span data-ttu-id="26432-164">デバイス id</span><span class="sxs-lookup"><span data-stu-id="26432-164">device id</span></span>
            </param>
        <param name="dataContainerId">
            <span data-ttu-id="26432-165">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-165">Required.</span></span> <span data-ttu-id="26432-166">削除する必要があるデータ コンテナーの id</span><span class="sxs-lookup"><span data-stu-id="26432-166">id of data container which needs to be deleted</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-167">必須。</span><span class="sxs-lookup"><span data-stu-id="26432-167">Required.</span></span> <span data-ttu-id="26432-168">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26432-168">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-169">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="26432-169">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.Get (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-170">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-170">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-171">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-171">Optional.</span></span>
            </param>
        <param name="dataContainerName">
            <span data-ttu-id="26432-172">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-172">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-173">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-173">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-174">データ コンテナーの get 応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="26432-174">The response model for the get of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, string dataContainerName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.GetAsync (operations, deviceId, dataContainerName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="dataContainerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-175">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-175">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-176">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-176">Optional.</span></span>
            </param>
        <param name="dataContainerName">
            <span data-ttu-id="26432-177">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-177">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-178">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-178">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-179">データ コンテナーの get 応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="26432-179">The response model for the get of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-180">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-180">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-181">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-181">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-182">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-182">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-183">データ コンテナーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="26432-183">The response model for the list of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DataContainerOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="26432-184">Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="26432-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="26432-185">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-185">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="26432-186">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26432-186">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="26432-187">データ コンテナーの一覧について応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="26432-187">The response model for the list of data containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>