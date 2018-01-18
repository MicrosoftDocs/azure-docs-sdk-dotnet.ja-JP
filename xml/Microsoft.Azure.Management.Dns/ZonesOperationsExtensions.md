<Type Name="ZonesOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ZonesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ZonesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ZonesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ZonesOperationsExtensions = class" />
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
            <span data-ttu-id="ffda5-101">ZonesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="ffda5-101">Extension methods for ZonesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDelete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-103">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-104">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-104">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-105">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-105">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-106">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-106">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="ffda5-107">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-107">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-108">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-108">Deletes a DNS zone.</span></span> <span data-ttu-id="ffda5-109">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-109">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="ffda5-110">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-110">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-112">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-113">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-113">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-114">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-114">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-115">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-115">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="ffda5-116">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-116">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-118">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-118">Deletes a DNS zone.</span></span> <span data-ttu-id="ffda5-119">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-119">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="ffda5-120">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-120">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone CreateOrUpdate(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IZonesOperations, resourceGroupName As String, zoneName As String, parameters As Zone, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Zone" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-122">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-123">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-123">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ffda5-124">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ffda5-124">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-125">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-125">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-126">常に現在のゾーンを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-126">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="ffda5-127">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-127">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="ffda5-128">設定 ' \*' 新しい DNS ゾーンを作成するが、既存のゾーンの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ffda5-128">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="ffda5-129">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-129">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-130">作成するか、DNS ゾーンを更新します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-130">Creates or updates a DNS zone.</span></span> <span data-ttu-id="ffda5-131">ゾーン内で DNS レコードを変更しません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-131">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, class Microsoft.Azure.Management.Dns.Models.Zone parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.Zone,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * Microsoft.Azure.Management.Dns.Models.Zone * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.Zone" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-133">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-134">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-134">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ffda5-135">CreateOrUpdate 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ffda5-135">Parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-136">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-136">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-137">常に現在のゾーンを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-137">Omit this value to always overwrite the current zone.</span></span> <span data-ttu-id="ffda5-138">変更できないように誤って overwritting 同時実行を最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-138">Specify the last-seen etag value to prevent accidentally overwritting any concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="ffda5-139">設定 ' \*' 新しい DNS ゾーンを作成するが、既存のゾーンの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ffda5-139">Set to '\*' to allow a new DNS zone to be created, but to prevent updating an existing zone.</span></span> <span data-ttu-id="ffda5-140">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-140">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-142">作成するか、DNS ゾーンを更新します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-142">Creates or updates a DNS zone.</span></span> <span data-ttu-id="ffda5-143">ゾーン内で DNS レコードを変更しません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-143">Does not modify DNS records within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IZonesOperations, resourceGroupName As String, zoneName As String, Optional ifMatch As String = null)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Delete (operations, resourceGroupName, zoneName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-145">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-146">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-146">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-147">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-147">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-148">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-148">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="ffda5-149">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-149">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-150">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-150">Deletes a DNS zone.</span></span> <span data-ttu-id="ffda5-151">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-151">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="ffda5-152">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-152">This operation cannot be undone.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-154">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-155">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-155">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="ffda5-156">DNS ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-156">The etag of the DNS zone.</span></span> <span data-ttu-id="ffda5-157">常に現在のゾーンを削除するには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-157">Omit this value to always delete the current zone.</span></span> <span data-ttu-id="ffda5-158">誤って削除したり、同時変更を防ぐために最後に、発生の etag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-158">Specify the last-seen etag value to prevent accidentally deleting any concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-160">DNS ゾーンを削除します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-160">Deletes a DNS zone.</span></span> <span data-ttu-id="ffda5-161">警告: ゾーン内のすべての DNS レコードも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ffda5-161">WARNING: All DNS records in the zone will also be deleted.</span></span> <span data-ttu-id="ffda5-162">削除操作は元に戻すことができません。</span><span class="sxs-lookup"><span data-stu-id="ffda5-162">This operation cannot be undone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.Zone Get (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.Zone Get(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IZonesOperations, resourceGroupName As String, zoneName As String) As Zone" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IZonesOperations * string * string -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.Get (operations, resourceGroupName, zoneName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.Zone</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-164">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-165">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-165">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-166">DNS ゾーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-166">Gets a DNS zone.</span></span> <span data-ttu-id="ffda5-167">ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-167">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; GetAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, string zoneName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-169">The name of the resource group.</span></span>
            </param>
        <param name="zoneName">
            <span data-ttu-id="ffda5-170">(末尾のドット) なしの DNS ゾーンの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-170">The name of the DNS zone (without a terminating dot).</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-172">DNS ゾーンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-172">Gets a DNS zone.</span></span> <span data-ttu-id="ffda5-173">ゾーンのプロパティが、ゾーン内でレコード セットではないを取得します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-173">Retrieves the zone properties, but not the record sets within the zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; List (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; List(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IZonesOperations, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.List (operations, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-174">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ffda5-175">返される DNS ゾーンの最大数。</span><span class="sxs-lookup"><span data-stu-id="ffda5-175">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="ffda5-176">指定されていない場合は、最大 100 個のゾーンを返します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-176">If not specified, returns up to 100 zones.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-177">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-177">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Dns.IZonesOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-178">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ffda5-179">返される DNS ゾーンの最大数。</span><span class="sxs-lookup"><span data-stu-id="ffda5-179">The maximum number of DNS zones to return.</span></span> <span data-ttu-id="ffda5-180">指定されていない場合は、最大 100 個のゾーンを返します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-180">If not specified, returns up to 100 zones.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-182">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-182">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroup(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IZonesOperations, resourceGroupName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-184">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ffda5-185">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-185">The maximum number of record sets to return.</span></span> <span data-ttu-id="ffda5-186">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-186">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-187">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-187">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ffda5-189">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="ffda5-189">The name of the resource group.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ffda5-190">返されるレコードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-190">The maximum number of record sets to return.</span></span> <span data-ttu-id="ffda5-191">指定されていない場合は、最大 100 のレコード セットを返します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-191">If not specified, returns up to 100 record sets.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-193">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-193">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ffda5-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-196">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-196">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ffda5-198">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-200">リソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-200">Lists the DNS zones within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt; ListNext(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext(Microsoft.Azure.Management.Dns.IZonesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IZonesOperations, nextPageLink As String) As IPage(Of Zone)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Dns.IZonesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-201">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ffda5-202">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-202">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-203">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-203">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Dns.IZonesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Dns.IZonesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Dns.IZonesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.ZonesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.ZonesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.Zone&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IZonesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ffda5-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ffda5-204">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ffda5-205">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ffda5-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ffda5-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ffda5-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ffda5-207">サブスクリプション内のすべてのリソース グループ内の DNS ゾーンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ffda5-207">Lists the DNS zones in all resource groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>