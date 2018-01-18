<Type Name="IContainerOperations" FullName="Microsoft.Azure.Management.BackupServices.IContainerOperations">
  <TypeSignature Language="C#" Value="public interface IContainerOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IContainerOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerOperations" />
  <TypeSignature Language="F#" Value="type IContainerOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="70e7b-101">Azure Backup の拡張機能のコンテナーの操作の定義。</span><span class="sxs-lookup"><span data-stu-id="70e7b-101">Definition of Container operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;" Usage="iContainerOperations.ListAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="parameters">
            <span data-ttu-id="70e7b-102">コンテナーのクエリのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="70e7b-102">Container query parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="70e7b-103">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-103">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="70e7b-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="70e7b-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70e7b-105">指定されたクエリのフィルター文字列に基づくすべてのコンテナーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-105">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="70e7b-106">CSMContainerListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="70e7b-106">The definition of a CSMContainerListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RefreshAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RefreshAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="70e7b-107">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-107">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="70e7b-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="70e7b-108">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70e7b-109">この検出をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="70e7b-109">Trigger the Discovery.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="70e7b-110">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="70e7b-110">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RegisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RegisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            <span data-ttu-id="70e7b-111">登録するコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="70e7b-111">Container to be register.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="70e7b-112">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-112">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="70e7b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="70e7b-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70e7b-114">コンテナーを登録します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-114">Register the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="70e7b-115">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="70e7b-115">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.UnregisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.UnregisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            <span data-ttu-id="70e7b-116">登録を解除するコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="70e7b-116">Container which we want to unregister.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="70e7b-117">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-117">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="70e7b-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="70e7b-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70e7b-119">コンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="70e7b-119">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="70e7b-120">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="70e7b-120">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>