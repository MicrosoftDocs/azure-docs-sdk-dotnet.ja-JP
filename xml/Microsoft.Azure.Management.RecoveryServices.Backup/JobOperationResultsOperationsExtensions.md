<Type Name="JobOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationResultsOperationsExtensions = class" />
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
            <span data-ttu-id="2638e-101">JobOperationResultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2638e-101">Extension methods for JobOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static void Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Get (operations As IJobOperationResultsOperations, vaultName As String, resourceGroupName As String, jobName As String, operationId As String)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, jobName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2638e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2638e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="2638e-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="2638e-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2638e-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="2638e-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="2638e-105">操作結果がフェッチされる、ジョブ名です。</span><span class="sxs-lookup"><span data-stu-id="2638e-105">Job name whose operation result has to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="2638e-106">その結果がフェッチされますが、操作を表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="2638e-106">OperationID which represents the operation whose result has to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2638e-107">任意の操作の結果をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="2638e-107">Fetches the result of any operation.</span></span>
            <span data-ttu-id="2638e-108">操作。</span><span class="sxs-lookup"><span data-stu-id="2638e-108">the operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations operations, string vaultName, string resourceGroupName, string jobName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, jobName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.JobOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IJobOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2638e-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2638e-109">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="2638e-110">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="2638e-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2638e-111">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="2638e-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="2638e-112">操作結果がフェッチされる、ジョブ名です。</span><span class="sxs-lookup"><span data-stu-id="2638e-112">Job name whose operation result has to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="2638e-113">その結果がフェッチされますが、操作を表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="2638e-113">OperationID which represents the operation whose result has to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2638e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2638e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2638e-115">任意の操作の結果をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="2638e-115">Fetches the result of any operation.</span></span>
            <span data-ttu-id="2638e-116">操作。</span><span class="sxs-lookup"><span data-stu-id="2638e-116">the operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>