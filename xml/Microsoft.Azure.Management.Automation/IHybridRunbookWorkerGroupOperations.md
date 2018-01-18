<Type Name="IHybridRunbookWorkerGroupOperations" FullName="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations">
  <TypeSignature Language="C#" Value="public interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="F#" Value="type IHybridRunbookWorkerGroupOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="85ce7-101">Automation hybrid runbook worker グループのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="85ce7-101">Service operation for automation hybrid runbook worker group.</span></span>  <span data-ttu-id="85ce7-102">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-102">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.DeleteAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
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
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="85ce7-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="85ce7-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="85ce7-104">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="85ce7-104">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="85ce7-105">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="85ce7-105">The hybrid runbook worker group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85ce7-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85ce7-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85ce7-107">Hybrid runbook worker グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="85ce7-107">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="85ce7-108">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-108">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="85ce7-109">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="85ce7-109">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.GetAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="85ce7-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="85ce7-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="85ce7-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="85ce7-111">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="85ce7-112">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="85ce7-112">The hybrid runbook worker group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85ce7-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85ce7-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85ce7-114">Hybrid runbook worker グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="85ce7-114">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="85ce7-115">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-115">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="85ce7-116">Get ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="85ce7-116">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="85ce7-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="85ce7-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="85ce7-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="85ce7-118">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85ce7-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85ce7-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85ce7-120">ハイブリッド runbook worker グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="85ce7-120">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="85ce7-121">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-121">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="85ce7-122">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="85ce7-122">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="85ce7-123">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="85ce7-123">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85ce7-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85ce7-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85ce7-125">ハイブリッド runbook worker グループの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="85ce7-125">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="85ce7-126">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-126">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="85ce7-127">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="85ce7-127">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.PatchAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.PatchAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="85ce7-128">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="85ce7-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="85ce7-129">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="85ce7-129">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="85ce7-130">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="85ce7-130">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="85ce7-131">Hybrid runbook worker グループ</span><span class="sxs-lookup"><span data-stu-id="85ce7-131">The hybrid runbook worker group</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="85ce7-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="85ce7-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="85ce7-133">Hybrid runbook worker グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="85ce7-133">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="85ce7-134">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="85ce7-134">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="85ce7-135">修正プログラム ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="85ce7-135">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>