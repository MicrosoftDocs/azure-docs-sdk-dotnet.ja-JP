<Type Name="IReplicationUsagesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations">
  <TypeSignature Language="C#" Value="public interface IReplicationUsagesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicationUsagesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicationUsagesOperations" />
  <TypeSignature Language="F#" Value="type IReplicationUsagesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76f60-101">ReplicationUsagesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="76f60-101">ReplicationUsagesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string vaultName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string vaultName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;&gt;" Usage="iReplicationUsagesOperations.ListWithHttpMessagesAsync (resourceGroupName, vaultName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76f60-102">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f60-102">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f60-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f60-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76f60-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76f60-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76f60-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76f60-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f60-106">資格情報コンテナーのレプリケーションの使用法をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="76f60-106">Fetches the replication usages of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76f60-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76f60-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76f60-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76f60-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76f60-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76f60-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>