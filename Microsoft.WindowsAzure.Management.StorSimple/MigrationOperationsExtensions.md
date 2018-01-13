<Type Name="MigrationOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MigrationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MigrationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MigrationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MigrationOperationsExtensions = class" />
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
            <span data-ttu-id="f8bf6-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="f8bf6-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-102">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-103">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-103">Required.</span></span> <span data-ttu-id="f8bf6-104">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-104">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-105">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-105">Required.</span></span> <span data-ttu-id="f8bf6-106">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-107">更新プログラム データ コンテナー statusThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット デバイスからのボリューム コンテナーの移行の状態を更新ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-107">Hydra spec for update data container statusThe rest api updates the status of volume container migration from target device to service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-108">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-109">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-109">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-110">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-110">Required.</span></span> <span data-ttu-id="f8bf6-111">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-111">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-112">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-112">Required.</span></span> <span data-ttu-id="f8bf6-113">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-113">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-114">更新プログラム データ コンテナー statusThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット デバイスからのボリューム コンテナーの移行の状態を更新ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-114">Hydra spec for update data container statusThe rest api updates the status of volume container migration from target device to service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-115">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-115">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-116">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-116">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-117">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-117">Required.</span></span> <span data-ttu-id="f8bf6-118">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-118">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-119">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-119">Required.</span></span> <span data-ttu-id="f8bf6-120">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-120">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-121">指定された構成でターゲット アプライアンスからすべてのデータ コンテナーのサービスへの確認 (コミットまたはロールバック) 状態を api の更新プログラム rest の更新プログラムの確認移行 statusThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-121">Hydra spec for update confirm migration statusThe rest api updates the confirm (commit/rollback) status from target appliance to service for all data container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-122">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-122">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-123">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-123">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-124">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-124">Required.</span></span> <span data-ttu-id="f8bf6-125">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-125">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-126">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-126">Required.</span></span> <span data-ttu-id="f8bf6-127">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-127">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-128">指定された構成でターゲット アプライアンスからすべてのデータ コンテナーのサービスへの確認 (コミットまたはロールバック) 状態を api の更新プログラム rest の更新プログラムの確認移行 statusThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-128">Hydra spec for update confirm migration statusThe rest api updates the confirm (commit/rollback) status from target appliance to service for all data container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-129">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-129">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-130">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-130">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-131">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-131">Required.</span></span> <span data-ttu-id="f8bf6-132">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-132">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-133">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-133">Required.</span></span> <span data-ttu-id="f8bf6-134">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-134">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-135">ヒュドラ spec の更新プログラムの移行計画 rest apiThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット アプライアンスから移行計画を更新します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-135">Hydra spec update migration plan rest apiThe rest api updates the migration plan from target appliance to service for all volume container(s) in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-136">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-136">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-137">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-137">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-138">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-138">Required.</span></span> <span data-ttu-id="f8bf6-139">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-139">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-140">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-140">Required.</span></span> <span data-ttu-id="f8bf6-141">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-141">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-142">ヒュドラ spec の更新プログラムの移行計画 rest apiThe rest api は、指定された構成ですべてのボリューム コンテナーのサービスを提供するターゲット アプライアンスから移行計画を更新します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-142">Hydra spec update migration plan rest apiThe rest api updates the migration plan from target appliance to service for all volume container(s) in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-143">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-143">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfirmMigration">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus ConfirmMigration (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus ConfirmMigration(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigration(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ConfirmMigration : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigration (operations, configId, confirmMigrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-144">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-144">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-145">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-145">Required.</span></span> <span data-ttu-id="f8bf6-146">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-146">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="confirmMigrationRequest">
            <span data-ttu-id="f8bf6-147">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-147">Required.</span></span> <span data-ttu-id="f8bf6-148">確認の移行要求は、ボリューム コンテナーとロールバック/コミット操作を実行するの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-148">The confirm migration request specifies the list of volume containers and rollback/commit operation to be performed</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-149">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-149">Required.</span></span> <span data-ttu-id="f8bf6-150">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-150">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-151">ヒュドラ仕様確認移行 rest apiThe rest api は、コミットまたはロールバックの指定された構成ですべてのデータ コンテナーの移行後のデータ コンテナーのことを確認</span><span class="sxs-lookup"><span data-stu-id="f8bf6-151">Hydra spec for confirm migration rest apiThe rest api confirms the commit or rollback of the migrated data containers for all data container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-152">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-152">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfirmMigrationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigrationAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ConfirmMigrationAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigrationAsync (operations, configId, confirmMigrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-153">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-153">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-154">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-154">Required.</span></span> <span data-ttu-id="f8bf6-155">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-155">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="confirmMigrationRequest">
            <span data-ttu-id="f8bf6-156">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-156">Required.</span></span> <span data-ttu-id="f8bf6-157">確認の移行要求は、ボリューム コンテナーとロールバック/コミット操作を実行するの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-157">The confirm migration request specifies the list of volume containers and rollback/commit operation to be performed</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-158">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-158">Required.</span></span> <span data-ttu-id="f8bf6-159">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-159">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-160">ヒュドラ仕様確認移行 rest apiThe rest api は、コミットまたはロールバックの指定された構成ですべてのデータ コンテナーの移行後のデータ コンテナーのことを確認</span><span class="sxs-lookup"><span data-stu-id="f8bf6-160">Hydra spec for confirm migration rest apiThe rest api confirms the commit or rollback of the migrated data containers for all data container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-161">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-161">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetAllMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetAllMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAllMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlan (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-162">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-162">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-163">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-163">Required.</span></span> <span data-ttu-id="f8bf6-164">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-164">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-165">ヒュドラ仕様のすべての移行 rest apiThe rest api が選択されている storsimple のリソースに対するインポート構成をすべての構成 id を返しますの取得します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-165">Hydra spec for Get all migration rest apiThe rest api returns the config ids for all configs imported against the selected storsimple resource</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-166">Get 移行計画の応答本文は rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-166">The response body for get migration plan rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAllMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlanAsync (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-167">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-167">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-168">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-168">Required.</span></span> <span data-ttu-id="f8bf6-169">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-169">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-170">ヒュドラ仕様のすべての移行 rest apiThe rest api が選択されている storsimple のリソースに対するインポート構成をすべての構成 id を返しますの取得します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-170">Hydra spec for Get all migration rest apiThe rest api returns the config ids for all configs imported against the selected storsimple resource</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-171">Get 移行計画の応答本文は rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-171">The response body for get migration plan rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList GetDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList GetDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-172">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-172">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-173">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-173">Required.</span></span> <span data-ttu-id="f8bf6-174">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-174">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-175">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-175">Required.</span></span> <span data-ttu-id="f8bf6-176">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-176">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-177">指定された構成ですべてのボリューム コンテナーのサービスからのボリューム コンテナーの移行状態の状態を api を返します。 rest の Get データ コンテナー移行 statusThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-177">Hydra spec for Get data container migration statusThe rest api returns the status of volume container migration status from service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-178">応答本文は、データ コンテナーの移行状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-178">The response body for get data container migration status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-179">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-179">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-180">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-180">Required.</span></span> <span data-ttu-id="f8bf6-181">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-181">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-182">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-182">Required.</span></span> <span data-ttu-id="f8bf6-183">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-183">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-184">指定された構成ですべてのボリューム コンテナーのサービスからのボリューム コンテナーの移行状態の状態を api を返します。 rest の Get データ コンテナー移行 statusThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-184">Hydra spec for Get data container migration statusThe rest api returns the status of volume container migration status from service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-185">応答本文は、データ コンテナーの移行状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-185">The response body for get data container migration status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus GetMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus GetMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-186">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-186">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-187">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-187">Required.</span></span> <span data-ttu-id="f8bf6-188">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-188">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-189">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-189">Required.</span></span> <span data-ttu-id="f8bf6-190">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-190">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-191">指定された構成ですべてのボリューム コンテナーのサービスからの確認 (コミットまたはロールバック) 状態を api rest get 確認移行ステータス rest apiThe のヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-191">Hydra spec for get confirm migration status rest apiThe rest api gets the confirm (commit/rollback) status from service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-192">応答本文の移行の状態を確認する rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-192">The response body of migration confirm status rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-193">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-193">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-194">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-194">Required.</span></span> <span data-ttu-id="f8bf6-195">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-195">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-196">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-196">Required.</span></span> <span data-ttu-id="f8bf6-197">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-197">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-198">指定された構成ですべてのボリューム コンテナーのサービスからの確認 (コミットまたはロールバック) 状態を api rest get 確認移行ステータス rest apiThe のヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-198">Hydra spec for get confirm migration status rest apiThe rest api gets the confirm (commit/rollback) status from service for all volume container in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-199">応答本文の移行の状態を確認する rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-199">The response body of migration confirm status rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-200">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-200">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-201">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-201">Required.</span></span> <span data-ttu-id="f8bf6-202">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-202">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-203">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-203">Required.</span></span> <span data-ttu-id="f8bf6-204">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-204">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-205">Get 移行プランのヒュドラ仕様 rest api get が指定された構成ですべてのボリューム コンテナーのサービスから、移行の計画</span><span class="sxs-lookup"><span data-stu-id="f8bf6-205">Hydra spec for get migration planThe rest api get the migration plan from service for all volume container(s) in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-206">Get 移行計画の応答本文は rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-206">The response body for get migration plan rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-207">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-207">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-208">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-208">Required.</span></span> <span data-ttu-id="f8bf6-209">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-209">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-210">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-210">Required.</span></span> <span data-ttu-id="f8bf6-211">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-211">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-212">Get 移行プランのヒュドラ仕様 rest api get が指定された構成ですべてのボリューム コンテナーのサービスから、移行の計画</span><span class="sxs-lookup"><span data-stu-id="f8bf6-212">Hydra spec for get migration planThe rest api get the migration plan from service for all volume container(s) in the specified config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-213">Get 移行計画の応答本文は rest api です。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-213">The response body for get migration plan rest api.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportLegacyApplianceConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse ImportLegacyApplianceConfig (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse ImportLegacyApplianceConfig(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfig(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ImportLegacyApplianceConfig : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfig (operations, configId, request, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-214">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-214">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-215">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-215">Required.</span></span> <span data-ttu-id="f8bf6-216">インポートされている構成の一意の id</span><span class="sxs-lookup"><span data-stu-id="f8bf6-216">Unique id for config being imported</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="f8bf6-217">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-217">Required.</span></span> <span data-ttu-id="f8bf6-218">レガシ アプライアンス構成をインポートします。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-218">Legacy appliance config to be imported</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-219">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-219">Required.</span></span> <span data-ttu-id="f8bf6-220">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-220">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-221">レガシ アプライアンスの構成でインポート ヒュドラ仕様は rest api です。Rest api サービスのレガシの構成のインポート</span><span class="sxs-lookup"><span data-stu-id="f8bf6-221">Hydra spec for import legacy appliance config rest api.The rest api imports the legacy config to the service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-222">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-222">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportLegacyApplianceConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfigAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ImportLegacyApplianceConfigAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfigAsync (operations, configId, request, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-223">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-223">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-224">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-224">Required.</span></span> <span data-ttu-id="f8bf6-225">インポートされている構成の一意の id</span><span class="sxs-lookup"><span data-stu-id="f8bf6-225">Unique id for config being imported</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="f8bf6-226">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-226">Required.</span></span> <span data-ttu-id="f8bf6-227">レガシ アプライアンス構成をインポートします。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-227">Legacy appliance config to be imported</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-228">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-228">Required.</span></span> <span data-ttu-id="f8bf6-229">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-229">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-230">レガシ アプライアンスの構成でインポート ヒュドラ仕様は rest api です。Rest api サービスのレガシの構成のインポート</span><span class="sxs-lookup"><span data-stu-id="f8bf6-230">Hydra spec for import legacy appliance config rest api.The rest api imports the legacy config to the service</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-231">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="f8bf6-231">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationImportDataContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus MigrationImportDataContainer (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus MigrationImportDataContainer(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainer(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member MigrationImportDataContainer : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainer (operations, configId, importDCRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-232">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-232">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-233">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-233">Required.</span></span> <span data-ttu-id="f8bf6-234">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-234">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="importDCRequest">
            <span data-ttu-id="f8bf6-235">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-235">Required.</span></span> <span data-ttu-id="f8bf6-236">インポート データ コンテナーからの要求を移行するデータ コンテナーの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-236">Import data container request which specifies the list of data containers to be migrated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-237">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-237">Required.</span></span> <span data-ttu-id="f8bf6-238">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-238">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-239">指定した設定ですべて/固有のデータ コンテナーのボリューム コンテナーの移行を api 開始 rest のインポート データ コンテナー rest apiThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-239">Hydra spec for import data container rest apiThe rest api initiates the migration of volume containers for all/specific data container(s) in the given config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-240">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-240">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationImportDataContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainerAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member MigrationImportDataContainerAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainerAsync (operations, configId, importDCRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-241">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-241">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-242">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-242">Required.</span></span> <span data-ttu-id="f8bf6-243">サービスへの構成のインポート中に指定された構成の一意の識別子</span><span class="sxs-lookup"><span data-stu-id="f8bf6-243">Unique identifier for config specified while importing the config to service</span></span>
            </param>
        <param name="importDCRequest">
            <span data-ttu-id="f8bf6-244">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-244">Required.</span></span> <span data-ttu-id="f8bf6-245">インポート データ コンテナーからの要求を移行するデータ コンテナーの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-245">Import data container request which specifies the list of data containers to be migrated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-246">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-246">Required.</span></span> <span data-ttu-id="f8bf6-247">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-247">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-248">指定した設定ですべて/固有のデータ コンテナーのボリューム コンテナーの移行を api 開始 rest のインポート データ コンテナー rest apiThe ヒュドラ仕様</span><span class="sxs-lookup"><span data-stu-id="f8bf6-248">Hydra spec for import data container rest apiThe rest api initiates the migration of volume containers for all/specific data container(s) in the given config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-249">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-249">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus StartMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus StartMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member StartMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlan (operations, startPlanRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-250">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-250">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="startPlanRequest">
            <span data-ttu-id="f8bf6-251">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-251">Required.</span></span> <span data-ttu-id="f8bf6-252">移行計画の要求モデルを開始します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-252">Start migration plan request model.</span></span> <span data-ttu-id="f8bf6-253">オブジェクトは、移行を予定を計算する必要があるボリューム コンテナーの一覧を渡します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-253">The object passes the list of volume container(s) whose migration ETA needs to calculated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-254">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-254">Required.</span></span> <span data-ttu-id="f8bf6-255">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-255">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-256">移行計画の開始のヒュドラ仕様 rest APIThe rest api で指定した設定ですべて/特定のボリューム コンテナーの移行にかかった時間の推定値の開始</span><span class="sxs-lookup"><span data-stu-id="f8bf6-256">Hydra spec for start migration plan rest APIThe rest api starts the estimation of time taken by migration for all/specific volume container(s) in the given config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-257">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-257">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member StartMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlanAsync (operations, startPlanRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-258">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-258">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="startPlanRequest">
            <span data-ttu-id="f8bf6-259">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-259">Required.</span></span> <span data-ttu-id="f8bf6-260">移行計画の要求モデルを開始します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-260">Start migration plan request model.</span></span> <span data-ttu-id="f8bf6-261">オブジェクトは、移行を予定を計算する必要があるボリューム コンテナーの一覧を渡します。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-261">The object passes the list of volume container(s) whose migration ETA needs to calculated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-262">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-262">Required.</span></span> <span data-ttu-id="f8bf6-263">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-263">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8bf6-264">移行計画の開始のヒュドラ仕様 rest APIThe rest api で指定した設定ですべて/特定のボリューム コンテナーの移行にかかった時間の推定値の開始</span><span class="sxs-lookup"><span data-stu-id="f8bf6-264">Hydra spec for start migration plan rest APIThe rest api starts the estimation of time taken by migration for all/specific volume container(s) in the given config</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8bf6-265">移行ジョブの状態の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-265">The response model for migration job status.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-266">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-266">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-267">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-267">Required.</span></span> <span data-ttu-id="f8bf6-268">configId</span><span class="sxs-lookup"><span data-stu-id="f8bf6-268">configId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-269">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-269">Required.</span></span> <span data-ttu-id="f8bf6-270">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-270">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-271">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-271">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-272">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-272">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-273">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-273">Required.</span></span> <span data-ttu-id="f8bf6-274">configId</span><span class="sxs-lookup"><span data-stu-id="f8bf6-274">configId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-275">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-275">Required.</span></span> <span data-ttu-id="f8bf6-276">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-276">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-277">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-277">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-278">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-278">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-279">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-279">Required.</span></span> <span data-ttu-id="f8bf6-280">移行のレガシの構成 id のステータスを更新する必要があることを確認</span><span class="sxs-lookup"><span data-stu-id="f8bf6-280">The legacy config id for which migration confirm status needs to be updated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-281">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-281">Required.</span></span> <span data-ttu-id="f8bf6-282">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-282">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-283">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-283">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-284">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-284">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-285">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-285">Required.</span></span> <span data-ttu-id="f8bf6-286">移行のレガシの構成 id のステータスを更新する必要があることを確認</span><span class="sxs-lookup"><span data-stu-id="f8bf6-286">The legacy config id for which migration confirm status needs to be updated</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-287">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-287">Required.</span></span> <span data-ttu-id="f8bf6-288">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-288">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-289">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-289">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-290">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-290">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-291">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-291">Required.</span></span> <span data-ttu-id="f8bf6-292">configId</span><span class="sxs-lookup"><span data-stu-id="f8bf6-292">configId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-293">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-293">Required.</span></span> <span data-ttu-id="f8bf6-294">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-294">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-295">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-295">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f8bf6-296">Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-296">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.</span></span>
            </param>
        <param name="configId">
            <span data-ttu-id="f8bf6-297">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-297">Required.</span></span> <span data-ttu-id="f8bf6-298">configId</span><span class="sxs-lookup"><span data-stu-id="f8bf6-298">configId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f8bf6-299">必須。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-299">Required.</span></span> <span data-ttu-id="f8bf6-300">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8bf6-300">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f8bf6-301">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="f8bf6-301">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>