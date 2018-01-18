<Type Name="IZonesOperations" FullName="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations">
  <TypeSignature Language="C#" Value="public interface IZonesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IZonesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IZonesOperations" />
  <TypeSignature Language="F#" Value="type IZonesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0537-101">ZonesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b0537-101">ZonesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string zoneName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string zoneName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt;" Usage="iZonesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, zoneName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0537-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-102">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="b0537-103">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-103">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b0537-104">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="b0537-104">The etag of the DNS zone.</span></span> <span data-ttu-id="b0537-105">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="b0537-105">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="b0537-106">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="b0537-106">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-109">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="b0537-109">Deletes a DNS zone.</span></span> <span data-ttu-id="b0537-110">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="b0537-110">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="b0537-111">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="b0537-111">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="iZonesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0537-115">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-115">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="b0537-116">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-116">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b0537-117">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b0537-117">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b0537-118">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="b0537-118">The etag of the DNS zone.</span></span> <span data-ttu-id="b0537-119">常に現在のゾーンを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="b0537-119">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="b0537-120">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="b0537-120">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="b0537-121">設定 ' \*' 新しい DNS ゾーンを作成するが、既存のゾーンの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="b0537-121">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="b0537-122">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="b0537-122">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-125">作成するか、DNS ゾーンを更新します。</span><span class="sxs-lookup"><span data-stu-id="b0537-125">Creates or updates a DNS zone.</span></span> <span data-ttu-id="b0537-126">ゾーン内で DNS レコードを変更しません。</span><span class="sxs-lookup"><span data-stu-id="b0537-126">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string zoneName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string zoneName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt;" Usage="iZonesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, zoneName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0537-130">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-130">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="b0537-131">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-131">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="b0537-132">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="b0537-132">The etag of the DNS zone.</span></span> <span data-ttu-id="b0537-133">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="b0537-133">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="b0537-134">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="b0537-134">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-137">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="b0537-137">Deletes a DNS zone.</span></span> <span data-ttu-id="b0537-138">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="b0537-138">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="b0537-139">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="b0537-139">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string zoneName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string zoneName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="iZonesOperations.GetWithHttpMessagesAsync (resourceGroupName, zoneName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0537-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-143">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="b0537-144">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-144">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-147">DNS ゾーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="b0537-147">Gets a DNS zone.</span></span> <span data-ttu-id="b0537-148">ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。</span><span class="sxs-lookup"><span data-stu-id="b0537-148">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;" Usage="iZonesOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b0537-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b0537-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-155">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b0537-155">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;" Usage="iZonesOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0537-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0537-159">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="b0537-160">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b0537-160">The maximum number of record sets to return.</span></span> <span data-ttu-id="b0537-161">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="b0537-161">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-164">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b0537-164">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;" Usage="iZonesOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b0537-168">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b0537-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-171">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b0537-171">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListWithHttpMessagesAsync (Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt; ListWithHttpMessagesAsync(valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IZonesOperations.ListWithHttpMessagesAsync(System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;" Usage="iZonesOperations.ListWithHttpMessagesAsync (top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="top">
            <span data-ttu-id="b0537-175">返される DNS ゾーンの最大数。</span><span class="sxs-lookup"><span data-stu-id="b0537-175">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="b0537-176">指定されていない場合は、最大 100 個のゾーンを返します。</span><span class="sxs-lookup"><span data-stu-id="b0537-176">If not specified, returns up to 100 zones.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b0537-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b0537-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0537-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0537-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0537-179">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b0537-179">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b0537-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b0537-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b0537-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b0537-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>