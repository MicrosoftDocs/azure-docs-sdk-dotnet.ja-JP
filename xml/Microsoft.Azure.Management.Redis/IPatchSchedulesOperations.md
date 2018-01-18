<Type Name="IPatchSchedulesOperations" FullName="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations">
  <TypeSignature Language="C#" Value="public interface IPatchSchedulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPatchSchedulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPatchSchedulesOperations" />
  <TypeSignature Language="F#" Value="type IPatchSchedulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60f86-101">PatchSchedulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="60f86-101">PatchSchedulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IPatchSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt;" Usage="iPatchSchedulesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, name, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60f86-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-102">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="60f86-103">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-103">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="60f86-104">Redis cache の更新プログラムの適用スケジュールを設定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="60f86-104">Parameters to set the patching schedule for Redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60f86-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="60f86-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60f86-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="60f86-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60f86-107">作成または Redis cache (Premium SKU が必要) の更新プログラムの適用スケジュールを置換します。</span><span class="sxs-lookup"><span data-stu-id="60f86-107">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60f86-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60f86-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60f86-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IPatchSchedulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPatchSchedulesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60f86-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-111">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="60f86-112">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-112">The name of the redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60f86-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="60f86-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60f86-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="60f86-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60f86-115">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="60f86-115">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60f86-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60f86-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.IPatchSchedulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt;" Usage="iPatchSchedulesOperations.GetWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="60f86-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="60f86-119">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="60f86-119">The name of the redis cache.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="60f86-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="60f86-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="60f86-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="60f86-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="60f86-122">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="60f86-122">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="60f86-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="60f86-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60f86-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60f86-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>