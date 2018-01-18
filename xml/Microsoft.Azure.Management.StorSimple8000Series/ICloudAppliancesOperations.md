<Type Name="ICloudAppliancesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations">
  <TypeSignature Language="C#" Value="public interface ICloudAppliancesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICloudAppliancesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICloudAppliancesOperations" />
  <TypeSignature Language="F#" Value="type ICloudAppliancesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7cb4-101">CloudAppliancesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-101">CloudAppliancesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginProvisionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginProvisionWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginProvisionWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations.BeginProvisionWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginProvisionWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCloudAppliancesOperations.BeginProvisionWithHttpMessagesAsync (parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="a7cb4-102">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="a7cb4-102">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a7cb4-103">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-103">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a7cb4-104">管理者名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-104">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a7cb4-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a7cb4-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a7cb4-107">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-107">Provisions cloud appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a7cb4-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a7cb4-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSupportedConfigurationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;&gt; ListSupportedConfigurationsWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;&gt; ListSupportedConfigurationsWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations.ListSupportedConfigurationsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSupportedConfigurationsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;&gt;" Usage="iCloudAppliancesOperations.ListSupportedConfigurationsWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a7cb4-110">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-110">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a7cb4-111">管理者名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-111">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a7cb4-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a7cb4-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a7cb4-114">リストは、クラウド アプライアンス モデルがサポートされているしでサポートされる構成です。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-114">Lists supported cloud appliance models and supported configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a7cb4-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a7cb4-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a7cb4-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ProvisionWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ProvisionWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations.ProvisionWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ProvisionWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCloudAppliancesOperations.ProvisionWithHttpMessagesAsync (parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="a7cb4-118">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="a7cb4-118">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a7cb4-119">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-119">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a7cb4-120">管理者名</span><span class="sxs-lookup"><span data-stu-id="a7cb4-120">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a7cb4-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a7cb4-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a7cb4-123">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-123">Provisions cloud appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a7cb4-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a7cb4-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a7cb4-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>