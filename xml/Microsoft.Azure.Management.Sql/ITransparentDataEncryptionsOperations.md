<Type Name="ITransparentDataEncryptionsOperations" FullName="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations">
  <TypeSignature Language="C#" Value="public interface ITransparentDataEncryptionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransparentDataEncryptionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransparentDataEncryptionsOperations" />
  <TypeSignature Language="F#" Value="type ITransparentDataEncryptionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99f95-101">TransparentDataEncryptionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="99f95-101">TransparentDataEncryptionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt;" Usage="iTransparentDataEncryptionsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="99f95-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="99f95-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="99f95-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="99f95-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="99f95-105">透過的なデータを設定すると、暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-105">The name of the database for which setting the transparent data encryption applies.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99f95-106">作成または更新の透過的なデータ暗号化の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="99f95-106">The required parameters for creating or updating transparent data encryption.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99f95-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99f95-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99f95-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99f95-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99f95-109">作成するか、データベースの透過的なデータ暗号化の構成を更新します。</span><span class="sxs-lookup"><span data-stu-id="99f95-109">Creates or updates a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99f95-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99f95-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99f95-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt;" Usage="iTransparentDataEncryptionsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;&gt;</ReturnType>
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
            <span data-ttu-id="99f95-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="99f95-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="99f95-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="99f95-115">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-115">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="99f95-116">透過的なデータ暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="99f95-116">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99f95-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99f95-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99f95-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99f95-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99f95-119">データベースの透過的なデータ暗号化の構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="99f95-119">Gets a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99f95-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99f95-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99f95-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99f95-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>