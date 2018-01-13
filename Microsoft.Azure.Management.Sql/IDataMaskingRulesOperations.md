<Type Name="IDataMaskingRulesOperations" FullName="Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations">
  <TypeSignature Language="C#" Value="public interface IDataMaskingRulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataMaskingRulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataMaskingRulesOperations" />
  <TypeSignature Language="F#" Value="type IDataMaskingRulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2621e-101">DataMaskingRulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="2621e-101">DataMaskingRulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string dataMaskingRuleName, class Microsoft.Azure.Management.Sql.Models.DataMaskingRule parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingRule,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingRule * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;" Usage="iDataMaskingRulesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, dataMaskingRuleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="dataMaskingRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="2621e-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="2621e-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="2621e-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="2621e-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="2621e-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-105">The name of the database.</span></span>
            </param>
        <param name="dataMaskingRuleName">
            <span data-ttu-id="2621e-106">データ マスク ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-106">The name of the data masking rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2621e-107">作成またはデータ マスキング ルールの更新の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2621e-107">The required parameters for creating or updating a data masking rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="2621e-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="2621e-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2621e-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2621e-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2621e-110">作成またはデータベースのデータ マスキング ルールを更新します。</span><span class="sxs-lookup"><span data-stu-id="2621e-110">Creates or updates a database data masking rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="2621e-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="2621e-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2621e-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations.ListByDatabaseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatabaseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;&gt;" Usage="iDataMaskingRulesOperations.ListByDatabaseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRule&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="2621e-114">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-114">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="2621e-115">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="2621e-115">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="2621e-116">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-116">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="2621e-117">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="2621e-117">The name of the database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="2621e-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="2621e-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2621e-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2621e-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2621e-120">データベースのデータ マスク ルールの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2621e-120">Gets a list of database data masking rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="2621e-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="2621e-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2621e-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2621e-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>