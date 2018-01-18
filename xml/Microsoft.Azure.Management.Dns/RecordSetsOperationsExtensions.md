<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0bd4-101">RecordSetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-101">Extension methods for RecordSetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-104">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-105">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-105">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-106">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-106">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-107">レコード セットの種類が SOA を更新できますが、作成されません (作成、DNS ゾーンの作成時に)。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-107">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="c0bd4-108">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-108">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0bd4-109">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-109">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-110">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-110">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-111">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-111">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="c0bd4-112">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-112">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c0bd4-113">設定 ' \*' セットを記録が、既存の更新を防ぐために新しいレコードを作成するセットを許可します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-113">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="c0bd4-114">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-114">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-115">作成またはレコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-115">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-117">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-117">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-118">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-118">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-119">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-119">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-120">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-120">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-121">レコード セットの種類が SOA を更新できますが、作成されません (作成、DNS ゾーンの作成時に)。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-121">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="c0bd4-122">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-122">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0bd4-123">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-123">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-124">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-124">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-125">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-125">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="c0bd4-126">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-126">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c0bd4-127">設定 ' \*' セットを記録が、既存の更新を防ぐために新しいレコードを作成するセットを許可します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-127">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="c0bd4-128">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-128">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-130">作成またはレコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-130">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-132">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-133">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-133">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-134">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-134">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-135">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-135">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-136">SOA を削除することはできません型のセットを記録 (することで DNS ゾーンを削除したときに、削除されます)。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-136">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="c0bd4-137">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-137">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-138">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-138">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-139">常に、現在のレコード セットを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-139">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="c0bd4-140">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-140">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-141">DNS ゾーンからレコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-141">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="c0bd4-142">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-142">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-144">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-145">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-145">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-146">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-146">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-147">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-147">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-148">SOA を削除することはできません型のセットを記録 (することで DNS ゾーンを削除したときに、削除されます)。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-148">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="c0bd4-149">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-149">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-150">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-150">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-151">常に、現在のレコード セットを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-151">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="c0bd4-152">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-152">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-154">DNS ゾーンからレコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-154">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="c0bd4-155">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-155">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Get (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Get(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-157">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-158">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-158">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-159">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-159">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-160">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-160">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-161">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-161">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-162">レコード セットを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-162">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-164">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-165">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-165">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-166">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-166">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-167">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-167">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-168">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-168">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-170">レコード セットを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-170">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZone">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZone (operations As IRecordSetsOperations, resourceGroupName As String, zoneName As String, Optional top As Nullable(Of Integer) = null, Optional recordsetnamesuffix As String = null) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZone : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone (operations, resourceGroupName, zoneName, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-172">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-173">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-173">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c0bd4-174">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-174">The maximum number of record sets to return.</span></span> <span data-ttu-id="c0bd4-175">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-175">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="c0bd4-176">レコード セット名を持つレコードをフィルター処理するためのサフィックスのラベルは、列挙型を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-176">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="c0bd4-177">このパラメーターを指定すると、列挙型はで終了するレコードのみを返します。&lt;recordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="c0bd4-177">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-178">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-178">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-180">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-180">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-181">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-181">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c0bd4-182">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-182">The maximum number of record sets to return.</span></span> <span data-ttu-id="c0bd4-183">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-183">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="c0bd4-184">レコード セット名を持つレコードをフィルター処理するためのサフィックスのラベルは、列挙型を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-184">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="c0bd4-185">このパラメーターを指定すると、列挙型はで終了するレコードのみを返します。&lt;recordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="c0bd4-185">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-187">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-187">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZoneNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0bd4-189">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-190">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-190">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0bd4-192">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-194">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-194">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="static member ListByType : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-196">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-197">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-197">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-198">レコードの種類は、列挙を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-198">The type of record sets to enumerate.</span></span> <span data-ttu-id="c0bd4-199">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-199">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c0bd4-200">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-200">The maximum number of record sets to return.</span></span> <span data-ttu-id="c0bd4-201">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-201">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="c0bd4-202">レコード セット名を持つレコードをフィルター処理するためのサフィックスのラベルは、列挙型を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-202">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="c0bd4-203">このパラメーターを指定すると、列挙型はで終了するレコードのみを返します。&lt;recordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="c0bd4-203">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-204">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-204">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-206">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-206">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-207">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-207">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-208">レコードの種類は、列挙を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-208">The type of record sets to enumerate.</span></span> <span data-ttu-id="c0bd4-209">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-209">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c0bd4-210">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-210">The maximum number of record sets to return.</span></span> <span data-ttu-id="c0bd4-211">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-211">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="recordsetnamesuffix">
            <span data-ttu-id="c0bd4-212">レコード セット名を持つレコードをフィルター処理するためのサフィックスのラベルは、列挙型を設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-212">The suffix label of the record set name that has to be used to filter the record set enumerations.</span></span> <span data-ttu-id="c0bd4-213">このパラメーターを指定すると、列挙型はで終了するレコードのみを返します。&lt;recordSetNameSuffix&gt;</span><span class="sxs-lookup"><span data-stu-id="c0bd4-213">If this parameter is specified, Enumeration will return only records that end with .&lt;recordSetNameSuffix&gt;</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-215">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-215">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTypeNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0bd4-217">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-218">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-218">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c0bd4-220">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-222">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-222">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Update (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Update(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-224">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-224">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-225">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-225">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-226">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-226">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-227">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-227">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-228">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-228">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0bd4-229">更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-229">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-230">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-230">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-231">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-231">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="c0bd4-232">誤って overwritting 同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-232">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-233">レコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-233">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0bd4-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0bd4-235">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-235">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="c0bd4-236">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-236">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="c0bd4-237">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-237">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="c0bd4-238">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-238">The type of DNS record in this record set.</span></span> <span data-ttu-id="c0bd4-239">使用可能な値が含まれます: 'A'、'AAAA'、'CAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="c0bd4-239">Possible values include: 'A', 'AAAA', 'CAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0bd4-240">更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-240">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0bd4-241">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-241">The etag of the record set.</span></span> <span data-ttu-id="c0bd4-242">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-242">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="c0bd4-243">誤って overwritting 同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-243">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0bd4-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0bd4-245">レコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="c0bd4-245">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>