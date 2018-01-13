<Type Name="IMarsContainerOperations" FullName="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations">
  <TypeSignature Language="C#" Value="public interface IMarsContainerOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMarsContainerOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMarsContainerOperations" />
  <TypeSignature Language="F#" Value="type IMarsContainerOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e828b-101">Azure Backup の拡張機能のコンテナーの操作の定義。</span><span class="sxs-lookup"><span data-stu-id="e828b-101">Definition of Container operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnableMarsContainerReregistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync (string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync(string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.EnableMarsContainerReregistrationAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableMarsContainerReregistrationAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iMarsContainerOperations.EnableMarsContainerReregistrationAsync (resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerId">
            <span data-ttu-id="e828b-102">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="e828b-102">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="e828b-103">登録要求を有効にします。</span><span class="sxs-lookup"><span data-stu-id="e828b-103">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e828b-104">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="e828b-104">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e828b-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e828b-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e828b-106">コンテナーの登録を有効にします。</span><span class="sxs-lookup"><span data-stu-id="e828b-106">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e828b-107">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="e828b-107">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync(string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.ListMarsContainersByTypeAndFriendlyNameAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMarsContainersByTypeAndFriendlyNameAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="iMarsContainerOperations.ListMarsContainersByTypeAndFriendlyNameAsync (resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerType">
            <span data-ttu-id="e828b-108">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="e828b-108">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="e828b-109">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="e828b-109">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e828b-110">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="e828b-110">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e828b-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e828b-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e828b-112">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e828b-112">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e828b-113">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="e828b-113">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync(string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.ListMarsContainersByTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMarsContainersByTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="iMarsContainerOperations.ListMarsContainersByTypeAsync (resourceGroupName, resourceName, containerType, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerType">
            <span data-ttu-id="e828b-114">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="e828b-114">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e828b-115">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="e828b-115">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e828b-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e828b-116">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e828b-117">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e828b-117">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e828b-118">Microsoft Azure Recovery Services (MARS) のコンテナーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="e828b-118">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync (string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync(string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.UnregisterMarsContainerAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterMarsContainerAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iMarsContainerOperations.UnregisterMarsContainerAsync (resourceGroupName, resourceName, containerId, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerId">
            <span data-ttu-id="e828b-119">MARS コンテナーの id。</span><span class="sxs-lookup"><span data-stu-id="e828b-119">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="e828b-120">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="e828b-120">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e828b-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e828b-121">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e828b-122">コンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="e828b-122">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e828b-123">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="e828b-123">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>