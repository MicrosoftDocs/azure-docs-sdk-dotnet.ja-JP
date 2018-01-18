<Type Name="ZonesOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ZonesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ZonesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ZonesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ZonesOperationsExtensions = class" />
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
            <span data-ttu-id="5fef1-101">ZonesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5fef1-101">Extension methods for ZonesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fef1-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="5fef1-104">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="5fef1-105">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="5fef1-105">The etag of the DNS zone.</span></span> <span data-ttu-id="5fef1-106">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-106">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="5fef1-107">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-107">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-109">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-109">Deletes a DNS zone.</span></span> <span data-ttu-id="5fef1-110">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="5fef1-110">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="5fef1-111">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="5fef1-111">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fef1-113">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-113">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="5fef1-114">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-114">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5fef1-115">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5fef1-115">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="5fef1-116">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="5fef1-116">The etag of the DNS zone.</span></span> <span data-ttu-id="5fef1-117">常に現在のゾーンを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-117">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="5fef1-118">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-118">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="5fef1-119">設定 ' \*' 新しい DNS ゾーンを作成するが、既存のゾーンの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="5fef1-119">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="5fef1-120">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="5fef1-120">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-122">作成するか、DNS ゾーンを更新します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-122">Creates or updates a DNS zone.</span></span> <span data-ttu-id="5fef1-123">ゾーン内で DNS レコードを変更しません。</span><span class="sxs-lookup"><span data-stu-id="5fef1-123">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fef1-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-125">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="5fef1-126">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-126">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="5fef1-127">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="5fef1-127">The etag of the DNS zone.</span></span> <span data-ttu-id="5fef1-128">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-128">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="5fef1-129">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-129">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-131">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-131">Deletes a DNS zone.</span></span> <span data-ttu-id="5fef1-132">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="5fef1-132">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="5fef1-133">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="5fef1-133">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; GetAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt; GetAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, string zoneName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fef1-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-135">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="5fef1-136">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-136">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-138">DNS ゾーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-138">Gets a DNS zone.</span></span> <span data-ttu-id="5fef1-139">ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-139">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-140">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="5fef1-141">返される DNS ゾーンの最大数。</span><span class="sxs-lookup"><span data-stu-id="5fef1-141">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="5fef1-142">指定されていない場合は、最大 100 個のゾーンを返します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-142">If not specified, returns up to 100 zones.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-144">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-144">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5fef1-146">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5fef1-146">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="5fef1-147">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-147">The maximum number of record sets to return.</span></span> <span data-ttu-id="5fef1-148">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-148">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-150">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-150">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-151">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5fef1-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5fef1-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-154">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-154">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Dns.Fluent.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Dns.Fluent.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.ZonesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5fef1-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5fef1-155">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5fef1-156">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5fef1-156">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5fef1-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5fef1-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5fef1-158">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="5fef1-158">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>