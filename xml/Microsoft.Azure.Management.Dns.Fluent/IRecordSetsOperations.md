<Type Name="IRecordSetsOperations" FullName="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations">
  <TypeSignature Language="C#" Value="public interface IRecordSetsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecordSetsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecordSetsOperations" />
  <TypeSignature Language="F#" Value="type IRecordSetsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d63b-101">RecordSetsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-101">RecordSetsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d63b-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-102">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="7d63b-103">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-103">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="7d63b-104">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-104">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="7d63b-105">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="7d63b-105">The type of DNS record in this record set.</span></span> <span data-ttu-id="7d63b-106">レコード セットの種類が SOA を更新できますが、作成されません (作成、DNS ゾーンの作成時に)。</span><span class="sxs-lookup"><span data-stu-id="7d63b-106">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span> <span data-ttu-id="7d63b-107">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="7d63b-107">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d63b-108">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d63b-108">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7d63b-109">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-109">The etag of the record set.</span></span> <span data-ttu-id="7d63b-110">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-110">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="7d63b-111">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-111">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="7d63b-112">設定 ' \*' セットを記録が、既存の更新を防ぐために新しいレコードを作成するセットを許可します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-112">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="7d63b-113">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-113">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-116">作成またはレコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-116">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d63b-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecordSetsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d63b-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-120">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="7d63b-121">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-121">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="7d63b-122">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-122">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="7d63b-123">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="7d63b-123">The type of DNS record in this record set.</span></span> <span data-ttu-id="7d63b-124">SOA を削除することはできません型のセットを記録 (することで DNS ゾーンを削除したときに、削除されます)。</span><span class="sxs-lookup"><span data-stu-id="7d63b-124">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span>
            <span data-ttu-id="7d63b-125">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="7d63b-125">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7d63b-126">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-126">The etag of the record set.</span></span> <span data-ttu-id="7d63b-127">常に、現在のレコード セットを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-127">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="7d63b-128">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-128">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-131">DNS ゾーンからレコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-131">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="7d63b-132">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="7d63b-132">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.GetWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d63b-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-135">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="7d63b-136">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-136">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="7d63b-137">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-137">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="7d63b-138">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="7d63b-138">The type of DNS record in this record set.</span></span> <span data-ttu-id="7d63b-139">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="7d63b-139">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-142">レコード セットを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-142">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d63b-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7d63b-146">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-146">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-149">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-149">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d63b-151">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-151">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-152">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-152">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync (string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByDnsZoneWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDnsZoneWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByDnsZoneWithHttpMessagesAsync (resourceGroupName, zoneName, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7d63b-153">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-153">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-156">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-156">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-157">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d63b-158">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync (string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt; ListByTypeWithHttpMessagesAsync(string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.ListByTypeWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Nullable{System.Int32},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTypeWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Nullable&lt;int&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;" Usage="iRecordSetsOperations.ListByTypeWithHttpMessagesAsync (resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="recordType">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="iRecordSetsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d63b-160">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-160">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="7d63b-161">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="7d63b-161">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="7d63b-162">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-162">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="7d63b-163">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="7d63b-163">The type of DNS record in this record set.</span></span> <span data-ttu-id="7d63b-164">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="7d63b-164">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d63b-165">更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7d63b-165">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7d63b-166">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="7d63b-166">The etag of the record set.</span></span> <span data-ttu-id="7d63b-167">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-167">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="7d63b-168">誤って overwritting 同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-168">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7d63b-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d63b-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d63b-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d63b-171">レコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="7d63b-171">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7d63b-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7d63b-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7d63b-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7d63b-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>