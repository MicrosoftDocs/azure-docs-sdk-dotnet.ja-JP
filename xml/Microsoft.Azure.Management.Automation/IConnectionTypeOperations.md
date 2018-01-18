<Type Name="IConnectionTypeOperations" FullName="Microsoft.Azure.Management.Automation.IConnectionTypeOperations">
  <TypeSignature Language="C#" Value="public interface IConnectionTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConnectionTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IConnectionTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConnectionTypeOperations" />
  <TypeSignature Language="F#" Value="type IConnectionTypeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0026b-101">オートメーション connectiontypes のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="0026b-101">Service operation for automation connectiontypes.</span></span>  <span data-ttu-id="0026b-102">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-102">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;" Usage="iConnectionTypeOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0026b-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="0026b-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0026b-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0026b-105">作成または更新 connectiontype 操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0026b-105">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0026b-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0026b-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0026b-107">Connectiontype は作成します。</span><span class="sxs-lookup"><span data-stu-id="0026b-107">Create a connectiontype.</span></span>  <span data-ttu-id="0026b-108">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-108">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0026b-109">作成または更新の接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="0026b-109">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string connectionTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string connectionTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iConnectionTypeOperations.DeleteAsync (resourceGroupName, automationAccount, connectionTypeName, cancellationToken)" />
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
        <Parameter Name="connectionTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0026b-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="0026b-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0026b-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-111">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="0026b-112">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-112">The name of connectiontype.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0026b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0026b-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0026b-114">クエリ文字列を削除します。</span><span class="sxs-lookup"><span data-stu-id="0026b-114">Delete the connectiontype.</span></span>  <span data-ttu-id="0026b-115">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-115">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0026b-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="0026b-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string connectionTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string connectionTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;" Usage="iConnectionTypeOperations.GetAsync (resourceGroupName, automationAccount, connectionTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0026b-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="0026b-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0026b-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-118">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="0026b-119">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-119">The name of connectiontype.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0026b-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0026b-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0026b-121">Connectiontype 名前によって識別されるクエリ文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="0026b-121">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="0026b-122">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-122">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0026b-123">接続の種類の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="0026b-123">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="iConnectionTypeOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0026b-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="0026b-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="0026b-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0026b-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0026b-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0026b-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0026b-127">Connectiontypes の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0026b-127">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="0026b-128">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-128">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0026b-129">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="0026b-129">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IConnectionTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="iConnectionTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="0026b-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="0026b-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0026b-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0026b-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0026b-132">Connectiontypes の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0026b-132">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="0026b-133">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="0026b-133">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0026b-134">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="0026b-134">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>