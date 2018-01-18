<Type Name="IVirtualMachineExtensionImagesOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionImagesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionImagesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionImagesOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionImagesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="21d91-101">VirtualMachineExtensionImagesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="21d91-101">VirtualMachineExtensionImagesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; GetWithHttpMessagesAsync (string location, string publisherName, string type, string version, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; GetWithHttpMessagesAsync(string location, string publisherName, string type, string version, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;" Usage="iVirtualMachineExtensionImagesOperations.GetWithHttpMessagesAsync (location, publisherName, type, version, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="21d91-102">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="21d91-102">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <param name="customHeaders">
            <span data-ttu-id="21d91-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="21d91-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21d91-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21d91-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21d91-105">仮想マシン拡張機能のイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="21d91-105">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="21d91-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="21d91-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="21d91-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTypesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt; ListTypesWithHttpMessagesAsync (string location, string publisherName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt; ListTypesWithHttpMessagesAsync(string location, string publisherName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations.ListTypesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTypesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt;" Usage="iVirtualMachineExtensionImagesOperations.ListTypesWithHttpMessagesAsync (location, publisherName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="21d91-109">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="21d91-109">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="customHeaders">
            <span data-ttu-id="21d91-110">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="21d91-110">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21d91-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21d91-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21d91-112">仮想マシン拡張機能のイメージの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="21d91-112">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="21d91-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="21d91-114">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="21d91-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt; ListVersionsWithHttpMessagesAsync (string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt; ListVersionsWithHttpMessagesAsync(string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations.ListVersionsWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListVersionsWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt;" Usage="iVirtualMachineExtensionImagesOperations.ListVersionsWithHttpMessagesAsync (location, publisherName, type, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="21d91-116">サポートされている Azure の地域の名前。</span><span class="sxs-lookup"><span data-stu-id="21d91-116">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="21d91-117">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="21d91-117">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="21d91-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="21d91-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21d91-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21d91-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21d91-120">仮想マシン拡張機能のイメージのバージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="21d91-120">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="21d91-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="21d91-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="21d91-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="21d91-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>