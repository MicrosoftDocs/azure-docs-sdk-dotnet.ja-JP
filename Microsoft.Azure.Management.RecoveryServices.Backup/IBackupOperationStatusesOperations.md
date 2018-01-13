<Type Name="IBackupOperationStatusesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupOperationStatusesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupOperationStatusesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupOperationStatusesOperations" />
  <TypeSignature Language="F#" Value="type IBackupOperationStatusesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6cb7e-101">BackupOperationStatusesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-101">BackupOperationStatusesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IBackupOperationStatusesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;" Usage="iBackupOperationStatusesOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, operationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="6cb7e-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6cb7e-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="6cb7e-104">操作を表している OperationID です。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-104">OperationID which represents the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cb7e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cb7e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cb7e-107">フェッチの状態のバックアップをトリガーするなどの操作、復元します。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-107">Fetches the status of an operation such as triggering a backup, restore.</span></span> <span data-ttu-id="6cb7e-108">進行中、完了または失敗の状態を指定できます。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-108">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="6cb7e-109">操作のすべての可能な状態の OperationStatus 列挙体を参照することができます。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-109">You can refer to the OperationStatus enum for all the possible states of an operation.</span></span> <span data-ttu-id="6cb7e-110">一部の操作は、ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-110">Some operations create jobs.</span></span> <span data-ttu-id="6cb7e-111">このメソッドは、操作が完了すると、ジョブの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-111">This method returns the list of jobs when the operation is complete.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cb7e-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cb7e-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cb7e-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cb7e-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>