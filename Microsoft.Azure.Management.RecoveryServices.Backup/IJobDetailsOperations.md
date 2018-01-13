<Type Name="IJobDetailsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IJobDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobDetailsOperations" />
  <TypeSignature Language="F#" Value="type IJobDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14e9a-101">JobDetailsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="14e9a-101">JobDetailsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IJobDetailsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;" Usage="iJobDetailsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, jobName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="14e9a-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="14e9a-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="14e9a-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="14e9a-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="14e9a-104">詳細については、フェッチするのには、ジョブの名前です。</span><span class="sxs-lookup"><span data-stu-id="14e9a-104">Name of the job whose details are to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="14e9a-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="14e9a-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="14e9a-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="14e9a-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="14e9a-107">ジョブに関連付けられている exteded 情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="14e9a-107">Gets exteded information associated with the job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="14e9a-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="14e9a-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="14e9a-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="14e9a-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="14e9a-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="14e9a-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>