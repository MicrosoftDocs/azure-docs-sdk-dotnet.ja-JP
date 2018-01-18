<Type Name="IProtectionContainerRefreshOperationResultsOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations">
  <TypeSignature Language="C#" Value="public interface IProtectionContainerRefreshOperationResultsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectionContainerRefreshOperationResultsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectionContainerRefreshOperationResultsOperations" />
  <TypeSignature Language="F#" Value="type IProtectionContainerRefreshOperationResultsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cc770-101">ProtectionContainerRefreshOperationResultsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="cc770-101">ProtectionContainerRefreshOperationResultsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerRefreshOperationResultsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iProtectionContainerRefreshOperationResultsOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, operationId, customHeaders, cancellationToken)" />
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
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="cc770-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="cc770-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cc770-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="cc770-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="cc770-104">コンテナーに関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="cc770-104">Fabric name associated with the container.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="cc770-105">その結果をフェッチする必要があります、操作に関連付けられている操作 ID。</span><span class="sxs-lookup"><span data-stu-id="cc770-105">Operation ID associated with the operation whose result needs to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cc770-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cc770-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cc770-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cc770-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cc770-108">BeginRefresh 操作によってトリガーされる、更新操作の結果を提供します。</span><span class="sxs-lookup"><span data-stu-id="cc770-108">Provides the result of the refresh operation triggered by the BeginRefresh operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cc770-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc770-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc770-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc770-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>