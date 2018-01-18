<Type Name="IRegisteredIdentitiesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations">
  <TypeSignature Language="C#" Value="public interface IRegisteredIdentitiesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRegisteredIdentitiesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRegisteredIdentitiesOperations" />
  <TypeSignature Language="F#" Value="type IRegisteredIdentitiesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="11756-101">RegisteredIdentitiesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="11756-101">RegisteredIdentitiesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vaultName, string identityName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vaultName, string identityName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRegisteredIdentitiesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vaultName, identityName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="identityName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="11756-102">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="11756-102">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="11756-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="11756-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="identityName">
            <span data-ttu-id="11756-104">コンテナーの名前、保護の登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="11756-104">Name of the protection container to unregister.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="11756-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="11756-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="11756-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="11756-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="11756-107">Recovery Services コンテナーから、指定したコンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="11756-107">Unregisters the given container from your Recovery Services vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="11756-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11756-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="11756-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="11756-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>