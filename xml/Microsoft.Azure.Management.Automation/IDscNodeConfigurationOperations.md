<Type Name="IDscNodeConfigurationOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeConfigurationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeConfigurationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeConfigurationOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeConfigurationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5f188-101">Automation dsc ノード構成のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="5f188-101">Service operation for automation dsc node configurations.</span></span>  <span data-ttu-id="5f188-102">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-102">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="iDscNodeConfigurationOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5f188-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5f188-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5f188-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5f188-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5f188-105">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="5f188-105">The create or update parameters for configuration.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f188-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5f188-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f188-107">ノード構成名で識別されるノードの構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="5f188-107">Create the node configuration identified by node configuration name.</span></span>  <span data-ttu-id="5f188-108">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-108">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5f188-109">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5f188-109">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string nodeConfigurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string nodeConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDscNodeConfigurationOperations.DeleteAsync (resourceGroupName, automationAccount, nodeConfigurationName, cancellationToken)" />
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
        <Parameter Name="nodeConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5f188-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5f188-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5f188-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5f188-111">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5f188-112">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5f188-112">The Dsc node configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f188-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5f188-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f188-114">ノードの構成での Dsc ノード構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="5f188-114">Delete the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5f188-115">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-115">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5f188-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="5f188-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string nodeConfigurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string nodeConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="iDscNodeConfigurationOperations.GetAsync (resourceGroupName, automationAccount, nodeConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5f188-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5f188-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5f188-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5f188-118">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5f188-119">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5f188-119">The Dsc node configuration name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f188-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5f188-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f188-121">ノードの構成での Dsc ノード構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="5f188-121">Retrieve the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5f188-122">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-122">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5f188-123">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5f188-123">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="iDscNodeConfigurationOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5f188-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5f188-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5f188-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5f188-125">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5f188-126">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5f188-126">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f188-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5f188-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f188-128">Dsc ノード構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5f188-128">Retrieve a list of dsc node configurations.</span></span>  <span data-ttu-id="5f188-129">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-129">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5f188-130">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5f188-130">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="iDscNodeConfigurationOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="5f188-131">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="5f188-131">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5f188-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5f188-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5f188-133">Dsc ノード configrations の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5f188-133">Retrieve next list of dsc node configrations.</span></span>  <span data-ttu-id="5f188-134">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5f188-134">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5f188-135">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5f188-135">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>