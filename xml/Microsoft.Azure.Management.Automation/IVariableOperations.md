<Type Name="IVariableOperations" FullName="Microsoft.Azure.Management.Automation.IVariableOperations">
  <TypeSignature Language="C#" Value="public interface IVariableOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVariableOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IVariableOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVariableOperations" />
  <TypeSignature Language="F#" Value="type IVariableOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5e62-101">オートメーション変数のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="c5e62-101">Service operation for automation variables.</span></span>  <span data-ttu-id="c5e62-102">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-102">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;" Usage="iVariableOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e62-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c5e62-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c5e62-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c5e62-105">変数を作成または更新操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c5e62-105">The parameters supplied to the create or update variable operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-107">変数を作成します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-107">Create a variable.</span></span>  <span data-ttu-id="c5e62-108">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-108">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-109">変数を作成または更新操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="c5e62-109">The response model for the create or update variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string variableName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string variableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iVariableOperations.DeleteAsync (resourceGroupName, automationAccount, variableName, cancellationToken)" />
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
        <Parameter Name="variableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e62-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c5e62-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c5e62-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-111">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="c5e62-112">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-112">The name of variable.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-114">変数を削除します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-114">Delete the variable.</span></span>  <span data-ttu-id="c5e62-115">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-115">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c5e62-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string variableName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string variableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;" Usage="iVariableOperations.GetAsync (resourceGroupName, automationAccount, variableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e62-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c5e62-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c5e62-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-118">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="c5e62-119">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-119">The name of variable.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-121">変数名で識別される変数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-121">Retrieve the variable identified by variable name.</span></span>  <span data-ttu-id="c5e62-122">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-122">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-123">変数の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="c5e62-123">The response model for the get variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="iVariableOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e62-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c5e62-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c5e62-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-127">変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-127">Retrieve a list of variables.</span></span>  <span data-ttu-id="c5e62-128">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-128">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-129">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="c5e62-129">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="iVariableOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="c5e62-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="c5e62-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-132">次の変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-132">Retrieve next list of variables.</span></span>  <span data-ttu-id="c5e62-133">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-133">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-134">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="c5e62-134">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IVariableOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariablePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.VariablePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iVariableOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariablePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c5e62-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c5e62-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="c5e62-136">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c5e62-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c5e62-137">Patch 変数操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c5e62-137">The parameters supplied to the patch variable operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5e62-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c5e62-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5e62-139">変数を更新します。</span><span class="sxs-lookup"><span data-stu-id="c5e62-139">Update a variable.</span></span>  <span data-ttu-id="c5e62-140">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="c5e62-140">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c5e62-141">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c5e62-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>