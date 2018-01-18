<Type Name="IElasticPoolDatabaseActivitiesOperations" FullName="Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations">
  <TypeSignature Language="C#" Value="public interface IElasticPoolDatabaseActivitiesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IElasticPoolDatabaseActivitiesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IElasticPoolDatabaseActivitiesOperations" />
  <TypeSignature Language="F#" Value="type IElasticPoolDatabaseActivitiesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d75db-101">ElasticPoolDatabaseActivitiesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d75db-101">ElasticPoolDatabaseActivitiesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByElasticPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;&gt; ListByElasticPoolWithHttpMessagesAsync (string resourceGroupName, string serverName, string elasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;&gt; ListByElasticPoolWithHttpMessagesAsync(string resourceGroupName, string serverName, string elasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations.ListByElasticPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByElasticPoolWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;&gt;" Usage="iElasticPoolDatabaseActivitiesOperations.ListByElasticPoolWithHttpMessagesAsync (resourceGroupName, serverName, elasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d75db-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d75db-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="d75db-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="d75db-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="d75db-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="d75db-104">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="d75db-105">弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="d75db-105">The name of the elastic pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d75db-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d75db-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d75db-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d75db-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d75db-108">エラスティック プール内のデータベースのアクティビティを返します。</span><span class="sxs-lookup"><span data-stu-id="d75db-108">Returns activity on databases inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d75db-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d75db-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d75db-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d75db-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d75db-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d75db-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>