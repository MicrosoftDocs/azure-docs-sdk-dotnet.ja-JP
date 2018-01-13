<Type Name="IDataSourceOperations" FullName="Microsoft.Azure.Management.BackupServices.IDataSourceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSourceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSourceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IDataSourceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSourceOperations" />
  <TypeSignature Language="F#" Value="type IDataSourceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="867d5-101">Azure Backup の拡張機能の操作をデータ ソースの定義。</span><span class="sxs-lookup"><span data-stu-id="867d5-101">Definition of DataSource operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.DisableProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.DisableProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="867d5-102">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="867d5-102">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="867d5-103">containerName です。</span><span class="sxs-lookup"><span data-stu-id="867d5-103">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="867d5-104">項目名。</span><span class="sxs-lookup"><span data-stu-id="867d5-104">itemName.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="867d5-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="867d5-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="867d5-106">指定した項目の保護を無効にします。</span><span class="sxs-lookup"><span data-stu-id="867d5-106">Disable protection for given item</span></span>
            </summary>
        <returns>
            <span data-ttu-id="867d5-107">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="867d5-107">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.EnableProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.EnableProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="867d5-108">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="867d5-108">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="867d5-109">containerName です。</span><span class="sxs-lookup"><span data-stu-id="867d5-109">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="867d5-110">項目名。</span><span class="sxs-lookup"><span data-stu-id="867d5-110">itemName.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="867d5-111">Set 保護要求が入力されます。</span><span class="sxs-lookup"><span data-stu-id="867d5-111">Set protection request input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="867d5-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="867d5-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="867d5-113">指定した項目の保護を有効にします。</span><span class="sxs-lookup"><span data-stu-id="867d5-113">Enable protection for given item.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="867d5-114">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="867d5-114">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.ListCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;" Usage="iDataSourceOperations.ListCSMAsync (resourceGroupName, resourceName, csmparameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="csmparameters">
            <span data-ttu-id="867d5-115">データ ソース クエリのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="867d5-115">DataSource query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="867d5-116">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="867d5-116">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="867d5-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="867d5-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="867d5-118">すべてのデータ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="867d5-118">Get the list of all Datasources.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="867d5-119">CSMProtectedItemListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="867d5-119">The definition of a CSMProtectedItemListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.UpdateProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.UpdateProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="867d5-120">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="867d5-120">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="867d5-121">containerName です。</span><span class="sxs-lookup"><span data-stu-id="867d5-121">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="867d5-122">項目名。</span><span class="sxs-lookup"><span data-stu-id="867d5-122">itemName.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="867d5-123">Set 保護要求が入力されます。</span><span class="sxs-lookup"><span data-stu-id="867d5-123">Set protection request input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="867d5-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="867d5-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="867d5-125">指定した項目の保護を有効にします。</span><span class="sxs-lookup"><span data-stu-id="867d5-125">Enable protection for given item.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="867d5-126">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="867d5-126">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>