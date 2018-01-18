<Type Name="VirtualMachineImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2367f-101">VirtualMachineImagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2367f-101">Extension methods for VirtualMachineImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.GetAsync (operations, location, publisherName, offer, skus, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;GetAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2367f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2367f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2367f-103">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="2367f-103">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="2367f-104">有効なイメージがパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="2367f-104">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="2367f-105">有効なイメージが発行者の提供。</span><span class="sxs-lookup"><span data-stu-id="2367f-105">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="2367f-106">有効なイメージの SKU。</span><span class="sxs-lookup"><span data-stu-id="2367f-106">A valid image SKU.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="2367f-107">有効なイメージの SKU バージョン。</span><span class="sxs-lookup"><span data-stu-id="2367f-107">A valid image SKU version.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2367f-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2367f-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2367f-109">仮想マシンのイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="2367f-109">Gets a virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListAsync (operations, location, publisherName, offer, skus, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2367f-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2367f-110">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2367f-111">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="2367f-111">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="2367f-112">有効なイメージがパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="2367f-112">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="2367f-113">有効なイメージが発行者の提供。</span><span class="sxs-lookup"><span data-stu-id="2367f-113">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="2367f-114">有効なイメージの SKU。</span><span class="sxs-lookup"><span data-stu-id="2367f-114">A valid image SKU.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="2367f-115">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2367f-115">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2367f-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2367f-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2367f-117">指定した場所、パブリッシャー、プラン、および SKU のすべての仮想マシン イメージのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2367f-117">Gets a list of all virtual machine image versions for the specified location, publisher, offer, and SKU.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListOffersAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListOffersAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListOffersAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOffersAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListOffersAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListOffersAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2367f-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2367f-118">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2367f-119">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="2367f-119">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="2367f-120">有効なイメージがパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="2367f-120">A valid image publisher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2367f-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2367f-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2367f-122">取得、指定した場所とパブリッシャーの仮想マシンのイメージの一覧を提供します。</span><span class="sxs-lookup"><span data-stu-id="2367f-122">Gets a list of virtual machine image offers for the specified location and publisher.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPublishersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListPublishersAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListPublishersAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListPublishersAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPublishersAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListPublishersAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListPublishersAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2367f-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2367f-123">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2367f-124">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="2367f-124">The name of a supported Azure region.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2367f-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2367f-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2367f-126">指定された Azure の場所の仮想マシン イメージのパブリッシャーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2367f-126">Gets a list of virtual machine image publishers for the specified Azure location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListSkusAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt; ListSkusAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListSkusAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions.ListSkusAsync (operations, location, publisherName, offer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineImagesOperationsExtensions/&lt;ListSkusAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineImageResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2367f-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2367f-127">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2367f-128">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="2367f-128">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="2367f-129">有効なイメージがパブリッシャーです。</span><span class="sxs-lookup"><span data-stu-id="2367f-129">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="2367f-130">有効なイメージが発行者の提供。</span><span class="sxs-lookup"><span data-stu-id="2367f-130">A valid image publisher offer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2367f-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2367f-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2367f-132">指定した場所、パブリッシャー、およびプランの仮想マシンのイメージの Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2367f-132">Gets a list of virtual machine image SKUs for the specified location, publisher, and offer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>