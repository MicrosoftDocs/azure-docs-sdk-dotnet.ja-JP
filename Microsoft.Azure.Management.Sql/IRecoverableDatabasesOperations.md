<Type Name="IRecoverableDatabasesOperations" FullName="Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations">
  <TypeSignature Language="C#" Value="public interface IRecoverableDatabasesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecoverableDatabasesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecoverableDatabasesOperations" />
  <TypeSignature Language="F#" Value="type IRecoverableDatabasesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95cc4-101">RecoverableDatabasesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="95cc4-101">RecoverableDatabasesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;" Usage="iRecoverableDatabasesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;</ReturnType>
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
            <span data-ttu-id="95cc4-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="95cc4-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="95cc4-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="95cc4-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="95cc4-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="95cc4-105">データベースの名前</span><span class="sxs-lookup"><span data-stu-id="95cc4-105">The name of the database</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="95cc4-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="95cc4-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="95cc4-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="95cc4-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="95cc4-108">表すデータベースの地理的バックアップをリソースでは、回復可能なデータベースを取得</span><span class="sxs-lookup"><span data-stu-id="95cc4-108">Gets a recoverable database, which is a resource representing a database's geo backup</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="95cc4-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="95cc4-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="95cc4-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;&gt;" Usage="iRecoverableDatabasesOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="95cc4-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="95cc4-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="95cc4-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="95cc4-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="95cc4-114">The name of the server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="95cc4-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="95cc4-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="95cc4-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="95cc4-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="95cc4-117">回復可能なデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="95cc4-117">Gets a list of recoverable databases</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="95cc4-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="95cc4-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="95cc4-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="95cc4-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>