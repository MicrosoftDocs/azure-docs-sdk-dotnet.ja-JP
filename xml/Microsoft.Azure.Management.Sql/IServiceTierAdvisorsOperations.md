<Type Name="IServiceTierAdvisorsOperations" FullName="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations">
  <TypeSignature Language="C#" Value="public interface IServiceTierAdvisorsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceTierAdvisorsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceTierAdvisorsOperations" />
  <TypeSignature Language="F#" Value="type IServiceTierAdvisorsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92672-101">ServiceTierAdvisorsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="92672-101">ServiceTierAdvisorsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;" Usage="iServiceTierAdvisorsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, serviceTierAdvisorName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="92672-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="92672-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="92672-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="92672-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="92672-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-105">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="92672-106">サービス層アドバイザーの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-106">The name of service tier advisor.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="92672-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="92672-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92672-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92672-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92672-109">サービス層アドバイザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="92672-109">Gets a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="92672-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="92672-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="92672-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations.ListByDatabaseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatabaseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;&gt;" Usage="iServiceTierAdvisorsOperations.ListByDatabaseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="92672-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="92672-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="92672-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="92672-115">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-115">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="92672-116">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="92672-116">The name of database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="92672-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="92672-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="92672-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="92672-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="92672-119">サービス層アドバイザー指定されたデータベースを返します。</span><span class="sxs-lookup"><span data-stu-id="92672-119">Returns service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="92672-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="92672-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="92672-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="92672-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>