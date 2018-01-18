<Type Name="ProtectionContainerRefreshOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionContainerRefreshOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionContainerRefreshOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionContainerRefreshOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionContainerRefreshOperationResultsOperationsExtensions = class" />
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
            <span data-ttu-id="1d1ac-101">ProtectionContainerRefreshOperationResultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-101">Extension methods for ProtectionContainerRefreshOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static void Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Get (operations As IProtectionContainerRefreshOperationResultsOperations, vaultName As String, resourceGroupName As String, fabricName As String, operationId As String)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1d1ac-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="1d1ac-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1d1ac-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="1d1ac-105">コンテナーに関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-105">Fabric name associated with the container.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="1d1ac-106">その結果をフェッチする必要があります、操作に関連付けられている操作 ID。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-106">Operation ID associated with the operation whose result needs to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d1ac-107">BeginRefresh 操作によってトリガーされる、更新操作の結果を提供します。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-107">Provides the result of the refresh operation triggered by the BeginRefresh operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerRefreshOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1d1ac-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-108">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="1d1ac-109">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1d1ac-110">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-110">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="1d1ac-111">コンテナーに関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-111">Fabric name associated with the container.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="1d1ac-112">その結果をフェッチする必要があります、操作に関連付けられている操作 ID。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-112">Operation ID associated with the operation whose result needs to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d1ac-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d1ac-114">BeginRefresh 操作によってトリガーされる、更新操作の結果を提供します。</span><span class="sxs-lookup"><span data-stu-id="1d1ac-114">Provides the result of the refresh operation triggered by the BeginRefresh operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>