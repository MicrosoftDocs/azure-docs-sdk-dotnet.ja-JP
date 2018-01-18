<Type Name="IProtectionPolicyOperationStatusesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations">
  <TypeSignature Language="C#" Value="public interface IProtectionPolicyOperationStatusesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectionPolicyOperationStatusesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectionPolicyOperationStatusesOperations" />
  <TypeSignature Language="F#" Value="type IProtectionPolicyOperationStatusesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ca701-101">ProtectionPolicyOperationStatusesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="ca701-101">ProtectionPolicyOperationStatusesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string policyName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string policyName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPolicyOperationStatusesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;" Usage="iProtectionPolicyOperationStatusesOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, policyName, operationId, customHeaders, cancellationToken)" />
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
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="ca701-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="ca701-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ca701-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ca701-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="ca701-104">バックアップ ポリシー名を持つ操作の状態をフェッチする必要があります。</span><span class="sxs-lookup"><span data-stu-id="ca701-104">Backup policy name whose operation's status needs to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="ca701-105">操作 ID をフェッチする必要がある状態が操作を表します。</span><span class="sxs-lookup"><span data-stu-id="ca701-105">Operation ID which represents an operation whose status needs to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ca701-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ca701-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ca701-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ca701-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ca701-108">バックアップ、復元など、非同期操作のステータスを提供します。</span><span class="sxs-lookup"><span data-stu-id="ca701-108">Provides the status of the asynchronous operations like backup, restore.</span></span> <span data-ttu-id="ca701-109">進行中、完了または失敗の状態を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ca701-109">The status can be in progress, completed or failed.</span></span> <span data-ttu-id="ca701-110">操作のすべての可能な状態の操作のステータスの列挙型を参照することができます。</span><span class="sxs-lookup"><span data-stu-id="ca701-110">You can refer to the Operation Status enum for all the possible states of an operation.</span></span> <span data-ttu-id="ca701-111">一部の操作は、ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="ca701-111">Some operations create jobs.</span></span> <span data-ttu-id="ca701-112">このメソッドは、操作に関連付けられているジョブの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="ca701-112">This method returns the list of jobs associated with operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ca701-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca701-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ca701-114">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca701-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ca701-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca701-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>