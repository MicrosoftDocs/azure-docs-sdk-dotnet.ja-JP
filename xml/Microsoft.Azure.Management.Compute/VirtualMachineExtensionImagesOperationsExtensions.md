<Type Name="VirtualMachineExtensionImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4e920-101">VirtualMachineExtensionImagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4e920-101">Extension methods for VirtualMachineExtensionImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage Get (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage Get(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String, type As String, version As String) As VirtualMachineExtensionImage" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.Get (operations, location, publisherName, type, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-103">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-103">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <summary>
            <span data-ttu-id="4e920-104">仮想マシン拡張機能のイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-104">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.GetAsync (operations, location, publisherName, type, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-105">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-106">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-106">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <param name="cancellationToken">
            <span data-ttu-id="4e920-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4e920-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e920-108">仮想マシン拡張機能のイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-108">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListTypes (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListTypes(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypes(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypes (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String) As IList(Of VirtualMachineExtensionImage)" />
      <MemberSignature Language="F#" Value="static member ListTypes : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypes (operations, location, publisherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-109">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-110">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-110">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <summary>
            <span data-ttu-id="4e920-111">仮想マシン拡張機能のイメージの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-111">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListTypesAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListTypesAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListTypesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-112">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-113">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-113">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="cancellationToken">
            <span data-ttu-id="4e920-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4e920-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e920-115">仮想マシン拡張機能のイメージの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-115">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVersions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListVersions (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListVersions(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersions(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVersions (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String, type As String, Optional odataQuery As ODataQuery(Of VirtualMachineExtensionImage) = null) As IList(Of VirtualMachineExtensionImage)" />
      <MemberSignature Language="F#" Value="static member ListVersions : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersions (operations, location, publisherName, type, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-116">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-117">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-117">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="4e920-118">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4e920-118">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e920-119">仮想マシン拡張機能のイメージのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-119">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListVersionsAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListVersionsAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVersionsAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync (operations, location, publisherName, type, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListVersionsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e920-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4e920-120">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4e920-121">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="4e920-121">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="4e920-122">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4e920-122">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4e920-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4e920-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e920-124">仮想マシン拡張機能のイメージのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4e920-124">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>