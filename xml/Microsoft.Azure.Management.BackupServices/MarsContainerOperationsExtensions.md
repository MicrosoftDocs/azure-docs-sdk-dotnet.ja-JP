<Type Name="MarsContainerOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MarsContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MarsContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MarsContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MarsContainerOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnableMarsContainerReregistration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistration : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-101">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-101">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-102">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-103">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-103">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="b2616-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-104">Required.</span></span> <span data-ttu-id="b2616-105">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="b2616-105">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="b2616-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-106">Required.</span></span> <span data-ttu-id="b2616-107">登録要求を有効にします。</span><span class="sxs-lookup"><span data-stu-id="b2616-107">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-108">Optional.</span></span> <span data-ttu-id="b2616-109">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-109">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-110">コンテナーの登録を有効にします。</span><span class="sxs-lookup"><span data-stu-id="b2616-110">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-111">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b2616-111">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMarsContainerReregistrationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistrationAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-112">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-112">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-113">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-114">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-114">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="b2616-115">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-115">Required.</span></span> <span data-ttu-id="b2616-116">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="b2616-116">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="b2616-117">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-117">Required.</span></span> <span data-ttu-id="b2616-118">登録要求を有効にします。</span><span class="sxs-lookup"><span data-stu-id="b2616-118">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-119">Optional.</span></span> <span data-ttu-id="b2616-120">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-120">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-121">コンテナーの登録を有効にします。</span><span class="sxs-lookup"><span data-stu-id="b2616-121">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-122">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b2616-122">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByType : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-123">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-123">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-124">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-124">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-125">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-125">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="b2616-126">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-126">Required.</span></span> <span data-ttu-id="b2616-127">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="b2616-127">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-128">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-128">Optional.</span></span> <span data-ttu-id="b2616-129">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-129">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-130">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2616-130">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-131">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="b2616-131">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyName : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-132">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-132">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-133">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-133">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-134">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-134">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="b2616-135">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-135">Required.</span></span> <span data-ttu-id="b2616-136">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="b2616-136">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="b2616-137">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-137">Required.</span></span> <span data-ttu-id="b2616-138">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="b2616-138">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-139">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-139">Optional.</span></span> <span data-ttu-id="b2616-140">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-140">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-141">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2616-141">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-142">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="b2616-142">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyNameAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-143">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-143">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-144">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-144">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-145">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-145">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="b2616-146">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-146">Required.</span></span> <span data-ttu-id="b2616-147">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="b2616-147">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="b2616-148">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-148">Required.</span></span> <span data-ttu-id="b2616-149">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="b2616-149">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-150">Optional.</span></span> <span data-ttu-id="b2616-151">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-151">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-152">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2616-152">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-153">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="b2616-153">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-154">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-154">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-155">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-155">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-156">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-156">Required.</span></span>
            </param>
        <param name="containerType">
            <span data-ttu-id="b2616-157">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-157">Required.</span></span> <span data-ttu-id="b2616-158">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="b2616-158">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-159">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-159">Optional.</span></span> <span data-ttu-id="b2616-160">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-160">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-161">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2616-161">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-162">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="b2616-162">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainer : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-163">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-163">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-164">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-164">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-165">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-165">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="b2616-166">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-166">Required.</span></span> <span data-ttu-id="b2616-167">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="b2616-167">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-168">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-168">Optional.</span></span> <span data-ttu-id="b2616-169">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-169">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-170">コンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="b2616-170">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-171">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b2616-171">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainerAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b2616-172">Microsoft.Azure.Management.BackupServices.IMarsContainerOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b2616-172">Reference to the Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b2616-173">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-173">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b2616-174">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-174">Required.</span></span>
            </param>
        <param name="containerId">
            <span data-ttu-id="b2616-175">必須。</span><span class="sxs-lookup"><span data-stu-id="b2616-175">Required.</span></span> <span data-ttu-id="b2616-176">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="b2616-176">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b2616-177">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b2616-177">Optional.</span></span> <span data-ttu-id="b2616-178">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b2616-178">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2616-179">コンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="b2616-179">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2616-180">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b2616-180">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>