<Type Name="IConnectionOperations" FullName="Microsoft.Azure.Management.Automation.IConnectionOperations">
  <TypeSignature Language="C#" Value="public interface IConnectionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConnectionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IConnectionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConnectionOperations" />
  <TypeSignature Language="F#" Value="type IConnectionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec2ca-101">オートメーション接続のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-101">Service operation for automation connections.</span></span>  <span data-ttu-id="ec2ca-102">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-102">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;" Usage="iConnectionOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec2ca-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ec2ca-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ec2ca-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec2ca-105">作成または更新の接続操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-105">The parameters supplied to the create or update connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-107">接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-107">Create a connection.</span></span>  <span data-ttu-id="ec2ca-108">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-108">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-109">作成または更新の接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-109">The response model for the create or update connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string connectionName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string connectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionOperations.DeleteAsync (resourceGroupName, automationAccount, connectionName, cancellationToken)" />
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
        <Parameter Name="connectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec2ca-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ec2ca-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ec2ca-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-111">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="ec2ca-112">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-112">The name of connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-114">接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-114">Delete the connection.</span></span>  <span data-ttu-id="ec2ca-115">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-115">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="ec2ca-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string connectionName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string connectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;" Usage="iConnectionOperations.GetAsync (resourceGroupName, automationAccount, connectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec2ca-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ec2ca-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ec2ca-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-118">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="ec2ca-119">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-119">The name of connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-121">接続の名前によって識別される接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-121">Retrieve the connection identified by connection name.</span></span>  <span data-ttu-id="ec2ca-122">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-122">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-123">接続の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-123">The response model for the get connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="iConnectionOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec2ca-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ec2ca-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ec2ca-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-127">接続の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-127">Retrieve a list of connections.</span></span>  <span data-ttu-id="ec2ca-128">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-128">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-129">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-129">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="iConnectionOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="ec2ca-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-132">接続の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-132">Retrieve next list of connections.</span></span>  <span data-ttu-id="ec2ca-133">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-133">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-134">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-134">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec2ca-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ec2ca-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ec2ca-136">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ec2ca-137">パラメーターは、修正プログラムへ接続操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-137">The parameters supplied to the patch a connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec2ca-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec2ca-139">接続を更新します。</span><span class="sxs-lookup"><span data-stu-id="ec2ca-139">Update a connection.</span></span>  <span data-ttu-id="ec2ca-140">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ec2ca-140">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ec2ca-141">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="ec2ca-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>