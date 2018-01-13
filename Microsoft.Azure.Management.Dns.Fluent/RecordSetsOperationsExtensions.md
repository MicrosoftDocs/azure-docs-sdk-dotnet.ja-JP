<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0bc6a-101">RecordSetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-101">Extension methods for RecordSetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0bc6a-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="0bc6a-104">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="0bc6a-105">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-105">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="0bc6a-106">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-106">The type of DNS record in this record set.</span></span> <span data-ttu-id="0bc6a-107">レコード セットの種類が SOA を更新できますが、作成されません (作成、DNS ゾーンの作成時に)。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-107">Record sets of type SOA can be updated but not created (they are created when the DNS zone is created).</span></span>
            <span data-ttu-id="0bc6a-108">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="0bc6a-108">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0bc6a-109">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-109">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="0bc6a-110">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-110">The etag of the record set.</span></span> <span data-ttu-id="0bc6a-111">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-111">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="0bc6a-112">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-112">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="0bc6a-113">設定 ' \*' セットを記録が、既存の更新を防ぐために新しいレコードを作成するセットを許可します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-113">Set to '\*' to allow a new record set to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="0bc6a-114">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-114">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-116">作成またはレコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-116">Creates or updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0bc6a-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-118">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="0bc6a-119">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-119">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="0bc6a-120">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-120">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="0bc6a-121">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-121">The type of DNS record in this record set.</span></span> <span data-ttu-id="0bc6a-122">SOA を削除することはできません型のセットを記録 (することで DNS ゾーンを削除したときに、削除されます)。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-122">Record sets of type SOA cannot be deleted (they are deleted when the DNS zone is deleted).</span></span> <span data-ttu-id="0bc6a-123">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="0bc6a-123">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="0bc6a-124">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-124">The etag of the record set.</span></span> <span data-ttu-id="0bc6a-125">常に、現在のレコード セットを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-125">Omit this value to always delete the current record set.</span></span> <span data-ttu-id="0bc6a-126">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-126">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-128">DNS ゾーンからレコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-128">Deletes a record set from a DNS zone.</span></span> <span data-ttu-id="0bc6a-129">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-129">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0bc6a-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-131">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="0bc6a-132">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-132">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="0bc6a-133">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-133">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="0bc6a-134">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-134">The type of DNS record in this record set.</span></span> <span data-ttu-id="0bc6a-135">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="0bc6a-135">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-137">レコード セットを取得します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-137">Gets a record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0bc6a-139">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-141">DNS ゾーン内のすべてのレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-141">Lists all record sets in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="recordType">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-142">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="0bc6a-143">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-143">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-145">DNS ゾーン内の指定した種類のレコード セットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-145">Lists the record sets of a specified type in a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0bc6a-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0bc6a-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-147">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="0bc6a-148">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-148">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="relativeRecordSetName">
            <span data-ttu-id="0bc6a-149">レコードの名前は、ゾーンの名前に対して設定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-149">The name of the record set, relative to the name of the zone.</span></span>
            </param>
        <param name="recordType">
            <span data-ttu-id="0bc6a-150">このレコード セット内の DNS レコードの型。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-150">The type of DNS record in this record set.</span></span> <span data-ttu-id="0bc6a-151">使用可能な値が含まれます: 'A'、'AAAA'、'CNAME'、'MX'、'NS'、'PTR'、'SOA'、'SRV'、'TXT'</span><span class="sxs-lookup"><span data-stu-id="0bc6a-151">Possible values include: 'A', 'AAAA', 'CNAME', 'MX', 'NS', 'PTR', 'SOA', 'SRV', 'TXT'</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0bc6a-152">更新操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-152">Parameters supplied to the Update operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="0bc6a-153">レコード セットの etag です。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-153">The etag of the record set.</span></span> <span data-ttu-id="0bc6a-154">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-154">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="0bc6a-155">誤って overwritting 同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-155">Specify the last-seen etag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0bc6a-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bc6a-157">レコードの DNS ゾーン内で設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="0bc6a-157">Updates a record set within a DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>