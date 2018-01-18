<Type Name="ExportJobsOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExportJobsOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExportJobsOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExportJobsOperationResultsOperationsExtensions = class" />
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
            <span data-ttu-id="10d7b-101">ExportJobsOperationResultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="10d7b-101">Extension methods for ExportJobsOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExportJobsOperationResultsOperations, vaultName As String, resourceGroupName As String, operationId As String) As OperationResultInfoBaseResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10d7b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10d7b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="10d7b-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="10d7b-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10d7b-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="10d7b-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="10d7b-105">エクスポート ジョブを表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="10d7b-105">OperationID which represents the export job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10d7b-106">エクスポート ジョブの API によってトリガーされる操作の操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="10d7b-106">Gets the operation result of operation triggered by Export Jobs API.</span></span> <span data-ttu-id="10d7b-107">操作が成功した場合も含まれますがアクセスするには、Blob と、SAS キーの URL。</span><span class="sxs-lookup"><span data-stu-id="10d7b-107">If the operation is successful, then it also contains URL of a Blob and a SAS key to access the same.</span></span> <span data-ttu-id="10d7b-108">Blob には、シリアル化された JSON 形式でエクスポートされたジョブが含まれています。</span><span class="sxs-lookup"><span data-stu-id="10d7b-108">The blob contains exported jobs in JSON serialized format.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations operations, string vaultName, string resourceGroupName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ExportJobsOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IExportJobsOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10d7b-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10d7b-109">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="10d7b-110">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="10d7b-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10d7b-111">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="10d7b-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="10d7b-112">エクスポート ジョブを表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="10d7b-112">OperationID which represents the export job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10d7b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10d7b-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10d7b-114">エクスポート ジョブの API によってトリガーされる操作の操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="10d7b-114">Gets the operation result of operation triggered by Export Jobs API.</span></span> <span data-ttu-id="10d7b-115">操作が成功した場合も含まれますがアクセスするには、Blob と、SAS キーの URL。</span><span class="sxs-lookup"><span data-stu-id="10d7b-115">If the operation is successful, then it also contains URL of a Blob and a SAS key to access the same.</span></span> <span data-ttu-id="10d7b-116">Blob には、シリアル化された JSON 形式でエクスポートされたジョブが含まれています。</span><span class="sxs-lookup"><span data-stu-id="10d7b-116">The blob contains exported jobs in JSON serialized format.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>