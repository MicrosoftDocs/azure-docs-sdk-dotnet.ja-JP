<Type Name="ProtectedItemOperationStatusesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemOperationStatusesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemOperationStatusesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemOperationStatusesOperationsExtensions = class" />
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
            <span data-ttu-id="ad32b-101">ProtectedItemOperationStatusesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="ad32b-101">Extension methods for ProtectedItemOperationStatusesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemOperationStatusesOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, operationId As String) As OperationStatus" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad32b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad32b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ad32b-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="ad32b-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad32b-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="ad32b-105">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="ad32b-105">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="ad32b-106">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="ad32b-106">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="ad32b-107">バックアップ項目の名前詳細情報がフェッチされます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-107">Backup item name whose details are to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="ad32b-108">OperationID では、状態をフェッチする必要があります、操作を表します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-108">OperationID represents the operation whose status needs to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad32b-109">フェッチの状態のバックアップをトリガーするなどの操作、復元します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-109">Fetches the status of an operation such as triggering a backup, restore.</span></span>
            <span data-ttu-id="ad32b-110">進行中、完了または失敗の状態を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-110">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="ad32b-111">操作のすべての可能な状態の OperationStatus 列挙体を参照することができます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-111">You can refer to the OperationStatus enum for all the possible states of the operation.</span></span> <span data-ttu-id="ad32b-112">一部の操作は、ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-112">Some operations create jobs.</span></span> <span data-ttu-id="ad32b-113">このメソッドは、操作に関連付けられているジョブの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-113">This method returns the list of jobs associated with the operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationStatusesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad32b-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ad32b-114">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ad32b-115">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="ad32b-115">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad32b-116">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-116">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="ad32b-117">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="ad32b-117">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="ad32b-118">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="ad32b-118">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="ad32b-119">バックアップ項目の名前詳細情報がフェッチされます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-119">Backup item name whose details are to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="ad32b-120">OperationID では、状態をフェッチする必要があります、操作を表します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-120">OperationID represents the operation whose status needs to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ad32b-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ad32b-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad32b-122">フェッチの状態のバックアップをトリガーするなどの操作、復元します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-122">Fetches the status of an operation such as triggering a backup, restore.</span></span>
            <span data-ttu-id="ad32b-123">進行中、完了または失敗の状態を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-123">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="ad32b-124">操作のすべての可能な状態の OperationStatus 列挙体を参照することができます。</span><span class="sxs-lookup"><span data-stu-id="ad32b-124">You can refer to the OperationStatus enum for all the possible states of the operation.</span></span> <span data-ttu-id="ad32b-125">一部の操作は、ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-125">Some operations create jobs.</span></span> <span data-ttu-id="ad32b-126">このメソッドは、操作に関連付けられているジョブの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="ad32b-126">This method returns the list of jobs associated with the operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>