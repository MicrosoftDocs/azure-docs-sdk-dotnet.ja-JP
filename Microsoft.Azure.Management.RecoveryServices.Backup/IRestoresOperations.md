<Type Name="IRestoresOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations">
  <TypeSignature Language="C#" Value="public interface IRestoresOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRestoresOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRestoresOperations" />
  <TypeSignature Language="F#" Value="type IRestoresOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03fac-101">RestoresOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="03fac-101">RestoresOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IRestoresOperations.TriggerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerWithHttpMessagesAsync : string * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRestoresOperations.TriggerWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequestResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="03fac-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="03fac-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="03fac-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="03fac-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="03fac-104">バックアップされた項目に関連付けられたファブリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="03fac-104">Fabric name associated with the backed up items.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="03fac-105">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="03fac-105">Container name associated with the backed up items.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="03fac-106">復元する項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="03fac-106">Backed up item to be restored.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="03fac-107">バックアップを復元するデータを表す回復ポイントの ID です。</span><span class="sxs-lookup"><span data-stu-id="03fac-107">Recovery point ID which represents the backed up data to be restored.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="03fac-108">復元要求のリソース</span><span class="sxs-lookup"><span data-stu-id="03fac-108">resource restore request</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03fac-109">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03fac-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03fac-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03fac-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03fac-111">指定したデータのバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="03fac-111">Restores the specified backed up data.</span></span> <span data-ttu-id="03fac-112">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="03fac-112">This is an asynchronous operation.</span></span> <span data-ttu-id="03fac-113">この API 呼び出しの状態を確認するには、GetProtectedItemOperationResult API を使用します。</span><span class="sxs-lookup"><span data-stu-id="03fac-113">To know the status of this API call, use GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03fac-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03fac-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03fac-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03fac-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>