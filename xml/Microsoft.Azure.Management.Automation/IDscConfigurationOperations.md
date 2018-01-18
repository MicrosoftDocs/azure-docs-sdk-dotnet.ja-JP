<Type Name="IDscConfigurationOperations" FullName="Microsoft.Azure.Management.Automation.IDscConfigurationOperations">
  <TypeSignature Language="C#" Value="public interface IDscConfigurationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscConfigurationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscConfigurationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscConfigurationOperations" />
  <TypeSignature Language="F#" Value="type IDscConfigurationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3908b-101">構成のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="3908b-101">Service operation for configurations.</span></span>  <span data-ttu-id="3908b-102">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-102">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;" Usage="iDscConfigurationOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3908b-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="3908b-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3908b-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3908b-105">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="3908b-105">The create or update parameters for configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-107">構成名で識別される構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="3908b-107">Create the configuration identified by configuration name.</span></span>  <span data-ttu-id="3908b-108">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-108">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-109">構成の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="3908b-109">The response model for the configuration create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string configurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string configurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDscConfigurationOperations.DeleteAsync (resourceGroupName, automationAccount, configurationName, cancellationToken)" />
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
        <Parameter Name="configurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3908b-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="3908b-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3908b-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-111">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="3908b-112">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-112">The configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-114">構成名で識別される、dsc 構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="3908b-114">Delete the dsc configuration identified by configuration name.</span></span>
            <span data-ttu-id="3908b-115">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-115">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="3908b-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string configurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string configurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;" Usage="iDscConfigurationOperations.GetAsync (resourceGroupName, automationAccount, configurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3908b-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="3908b-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3908b-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-118">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="3908b-119">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-119">The configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-121">構成名で識別される構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="3908b-121">Retrieve the configuration identified by configuration name.</span></span>  <span data-ttu-id="3908b-122">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-122">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-123">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="3908b-123">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync (string resourceGroupName, string automationAccount, string configurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync(string resourceGroupName, string automationAccount, string configurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.GetContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;" Usage="iDscConfigurationOperations.GetContentAsync (resourceGroupName, automationAccount, configurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3908b-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="3908b-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3908b-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-125">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="3908b-126">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-126">The configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-128">構成名で識別される、構成スクリプトを取得します。</span><span class="sxs-lookup"><span data-stu-id="3908b-128">Retrieve the configuration script identified by configuration name.</span></span>
            <span data-ttu-id="3908b-129">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-129">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-130">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="3908b-130">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="iDscConfigurationOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3908b-131">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="3908b-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3908b-132">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3908b-132">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-134">構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3908b-134">Retrieve a list of configurations.</span></span>  <span data-ttu-id="3908b-135">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-135">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-136">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="3908b-136">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscConfigurationOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="iDscConfigurationOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3908b-137">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="3908b-137">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3908b-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3908b-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3908b-139">構成の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="3908b-139">Retrieve next list of configurations.</span></span>  <span data-ttu-id="3908b-140">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="3908b-140">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3908b-141">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="3908b-141">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>