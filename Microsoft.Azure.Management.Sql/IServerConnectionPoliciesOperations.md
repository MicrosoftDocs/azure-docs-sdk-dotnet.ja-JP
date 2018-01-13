<Type Name="IServerConnectionPoliciesOperations" FullName="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IServerConnectionPoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServerConnectionPoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServerConnectionPoliciesOperations" />
  <TypeSignature Language="F#" Value="type IServerConnectionPoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eda7d-101">ServerConnectionPoliciesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="eda7d-101">ServerConnectionPoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt;" Usage="iServerConnectionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eda7d-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eda7d-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eda7d-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eda7d-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="eda7d-104">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eda7d-105">セキュリティで保護された接続ポリシーを更新するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="eda7d-105">The required parameters for updating a secure connection policy.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="eda7d-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="eda7d-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eda7d-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eda7d-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eda7d-108">作成するか、サーバーの接続のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="eda7d-108">Creates or updates the server's connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="eda7d-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="eda7d-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eda7d-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt;" Usage="iServerConnectionPoliciesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eda7d-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eda7d-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="eda7d-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="eda7d-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="eda7d-114">The name of the server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="eda7d-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="eda7d-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eda7d-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eda7d-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eda7d-117">サーバーのセキュリティで保護された接続ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="eda7d-117">Gets the server's secure connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="eda7d-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="eda7d-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eda7d-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eda7d-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>