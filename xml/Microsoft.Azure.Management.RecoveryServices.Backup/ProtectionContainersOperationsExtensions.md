<Type Name="ProtectionContainersOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionContainersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionContainersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionContainersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d8f0-101">ProtectionContainersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-101">Extension methods for ProtectionContainersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionContainersOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String) As ProtectionContainerResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d8f0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9d8f0-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d8f0-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="9d8f0-105">コンテナーが属するファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-105">Name of the fabric where the container belongs.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="9d8f0-106">詳細をフェッチする必要があるコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-106">Name of the container whose details need to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d8f0-107">復旧サービス コンテナーに登録されている特定のコンテナーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-107">Gets details of the specific container registered to your Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d8f0-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-108">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9d8f0-109">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d8f0-110">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-110">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="9d8f0-111">コンテナーが属するファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-111">Name of the fabric where the container belongs.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="9d8f0-112">詳細をフェッチする必要があるコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-112">Name of the container whose details need to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d8f0-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d8f0-114">復旧サービス コンテナーに登録されている特定のコンテナーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-114">Gets details of the specific container registered to your Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public static void Refresh (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Refresh(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Refresh(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Refresh (operations As IProtectionContainersOperations, vaultName As String, resourceGroupName As String, fabricName As String)" />
      <MemberSignature Language="F#" Value="static member Refresh : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.Refresh (operations, vaultName, resourceGroupName, fabricName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d8f0-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-115">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9d8f0-116">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-116">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d8f0-117">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="9d8f0-118">ファブリック名には、コンテナーが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-118">Fabric name associated the container.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d8f0-119">Recovery Services コンテナーにバックアップすることができます、サブスクリプション内のすべてのコンテナーを検出します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-119">Discovers all the containers in the subscription that can be backed up to Recovery Services Vault.</span></span> <span data-ttu-id="9d8f0-120">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-120">This is an asynchronous operation.</span></span> <span data-ttu-id="9d8f0-121">操作の状態を確認するには、GetRefreshOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-121">To know the status of the operation, call GetRefreshOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RefreshAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations operations, string vaultName, string resourceGroupName, string fabricName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.RefreshAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions.RefreshAsync (operations, vaultName, resourceGroupName, fabricName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainersOperationsExtensions/&lt;RefreshAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d8f0-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-122">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="9d8f0-123">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-123">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d8f0-124">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-124">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="9d8f0-125">ファブリック名には、コンテナーが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-125">Fabric name associated the container.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d8f0-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d8f0-127">Recovery Services コンテナーにバックアップすることができます、サブスクリプション内のすべてのコンテナーを検出します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-127">Discovers all the containers in the subscription that can be backed up to Recovery Services Vault.</span></span> <span data-ttu-id="9d8f0-128">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-128">This is an asynchronous operation.</span></span> <span data-ttu-id="9d8f0-129">操作の状態を確認するには、GetRefreshOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="9d8f0-129">To know the status of the operation, call GetRefreshOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>