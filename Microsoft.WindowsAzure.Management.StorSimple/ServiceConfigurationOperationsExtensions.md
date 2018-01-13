<Type Name="ServiceConfigurationOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServiceConfigurationOperationsExtensions = class" />
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
            <span data-ttu-id="04ce1-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="04ce1-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreating(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreating(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreating (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-102">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="04ce1-103">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-103">Required.</span></span> <span data-ttu-id="04ce1-104">パラメーターは、ストレージ アカウントの作成を開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-104">Parameters supplied to the Begin Creating Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="04ce1-105">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-105">Required.</span></span> <span data-ttu-id="04ce1-106">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="04ce1-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04ce1-107">ストレージ アカウントの作成を開始操作は、Azure で新しいストレージ アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-107">The Begin Creating Storage Account operation creates a new storage account in Azure.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04ce1-108">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="04ce1-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.BeginCreatingAsync (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-109">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-109">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="04ce1-110">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-110">Required.</span></span> <span data-ttu-id="04ce1-111">パラメーターは、ストレージ アカウントの作成を開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-111">Parameters supplied to the Begin Creating Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="04ce1-112">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-112">Required.</span></span> <span data-ttu-id="04ce1-113">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="04ce1-113">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04ce1-114">ストレージ アカウントの作成を開始操作は、Azure で新しいストレージ アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-114">The Begin Creating Storage Account operation creates a new storage account in Azure.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04ce1-115">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="04ce1-115">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Create (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-116">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-116">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="04ce1-117">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-117">Required.</span></span> <span data-ttu-id="04ce1-118">パラメーターは、ストレージ アカウントの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-118">Parameters supplied to the Create Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="04ce1-119">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-119">Required.</span></span> <span data-ttu-id="04ce1-120">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="04ce1-120">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="04ce1-121">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="04ce1-121">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.CreateAsync (operations, serviceConfiguration, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-122">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-122">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="serviceConfiguration">
            <span data-ttu-id="04ce1-123">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-123">Required.</span></span> <span data-ttu-id="04ce1-124">パラメーターは、ストレージ アカウントの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="04ce1-124">Parameters supplied to the Create Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="04ce1-125">必須。</span><span class="sxs-lookup"><span data-stu-id="04ce1-125">Required.</span></span> <span data-ttu-id="04ce1-126">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="04ce1-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="04ce1-127">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="04ce1-127">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServiceConfigurationOperations, customeRequestHeaders As CustomRequestHeaders) As ServiceConfigurationResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.Get (operations, customeRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-128">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-128">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="customeRequestHeaders">
            <span data-ttu-id="04ce1-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="04ce1-129">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="04ce1-130">そのリソースに関するサービスの構成についての情報</span><span class="sxs-lookup"><span data-stu-id="04ce1-130">Info about the service configuration regarding the resource</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IServiceConfigurationOperations, customeRequestHeaders As CustomRequestHeaders) As Task(Of ServiceConfigurationResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ServiceConfigurationOperationsExtensions.GetAsync (operations, customeRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" RefType="this" />
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="04ce1-131">Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="04ce1-131">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.</span></span>
            </param>
        <param name="customeRequestHeaders">
            <span data-ttu-id="04ce1-132">省略可能。</span><span class="sxs-lookup"><span data-stu-id="04ce1-132">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="04ce1-133">そのリソースに関するサービスの構成についての情報</span><span class="sxs-lookup"><span data-stu-id="04ce1-133">Info about the service configuration regarding the resource</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>