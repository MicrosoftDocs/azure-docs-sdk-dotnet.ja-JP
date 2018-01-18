<Type Name="IScheduleOperations" FullName="Microsoft.Azure.Management.Automation.IScheduleOperations">
  <TypeSignature Language="C#" Value="public interface IScheduleOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IScheduleOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IScheduleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IScheduleOperations" />
  <TypeSignature Language="F#" Value="type IScheduleOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76644-101">Automation のスケジュールのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="76644-101">Service operation for automation schedules.</span></span>  <span data-ttu-id="76644-102">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-102">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt;" Usage="iScheduleOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76644-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76644-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76644-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76644-105">作成または更新のスケジュール操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="76644-105">The parameters supplied to the create or update schedule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-107">スケジュールを作成します。</span><span class="sxs-lookup"><span data-stu-id="76644-107">Create a schedule.</span></span>  <span data-ttu-id="76644-108">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-108">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-109">作成または更新のスケジュール操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76644-109">The response model for the create or update schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string scheduleName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string scheduleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iScheduleOperations.DeleteAsync (resourceGroupName, automationAccount, scheduleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76644-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76644-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76644-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-111">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="76644-112">スケジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-112">The schedule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-114">スケジュールの名前によって識別されるスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="76644-114">Delete the schedule identified by schedule name.</span></span>  <span data-ttu-id="76644-115">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-115">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="76644-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string scheduleName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string scheduleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt;" Usage="iScheduleOperations.GetAsync (resourceGroupName, automationAccount, scheduleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="scheduleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76644-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76644-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76644-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-118">The automation account name.</span></span>
            </param>
        <param name="scheduleName">
            <span data-ttu-id="76644-119">スケジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-119">The schedule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-121">スケジュールの名前によって識別されるスケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="76644-121">Retrieve the schedule identified by schedule name.</span></span>  <span data-ttu-id="76644-122">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-122">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-123">スケジュールの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76644-123">The response model for the get schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;" Usage="iScheduleOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76644-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76644-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76644-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-127">スケジュールの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76644-127">Retrieve a list of schedules.</span></span>  <span data-ttu-id="76644-128">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-128">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-129">一覧のスケジュール操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76644-129">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;" Usage="iScheduleOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="76644-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="76644-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-132">スケジュールの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76644-132">Retrieve next list of schedules.</span></span>  <span data-ttu-id="76644-133">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-133">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-134">一覧のスケジュール操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76644-134">The response model for the list schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IScheduleOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iScheduleOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.SchedulePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76644-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76644-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76644-136">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76644-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76644-137">修正プログラムのスケジュール操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="76644-137">The parameters supplied to the patch schedule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76644-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76644-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76644-139">スケジュールの名前によって識別されるスケジュールを更新します。</span><span class="sxs-lookup"><span data-stu-id="76644-139">Update the schedule identified by schedule name.</span></span>  <span data-ttu-id="76644-140">(詳細については http://aka.ms/azureautomationsdk/scheduleoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76644-140">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76644-141">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="76644-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>