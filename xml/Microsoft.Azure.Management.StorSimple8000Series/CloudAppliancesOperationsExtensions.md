<Type Name="CloudAppliancesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CloudAppliancesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudAppliancesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudAppliancesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CloudAppliancesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e0f3-101">CloudAppliancesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-101">Extension methods for CloudAppliancesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginProvision">
      <MemberSignature Language="C#" Value="public static void BeginProvision (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginProvision(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.BeginProvision(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginProvision (operations As ICloudAppliancesOperations, parameters As CloudAppliance, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginProvision : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.BeginProvision (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6e0f3-103">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="6e0f3-103">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-105">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-106">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-106">Provisions cloud appliance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginProvisionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginProvisionAsync (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginProvisionAsync(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.BeginProvisionAsync(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginProvisionAsync : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.BeginProvisionAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions/&lt;BeginProvisionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6e0f3-108">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="6e0f3-108">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-109">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-109">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-110">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-110">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6e0f3-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-112">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-112">Provisions cloud appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSupportedConfigurations">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt; ListSupportedConfigurations (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt; ListSupportedConfigurations(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ListSupportedConfigurations(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSupportedConfigurations (operations As ICloudAppliancesOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of CloudApplianceConfiguration)" />
      <MemberSignature Language="F#" Value="static member ListSupportedConfigurations : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ListSupportedConfigurations (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-114">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-114">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-115">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-115">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-116">リストは、クラウド アプライアンス モデルがサポートされているしでサポートされる構成です。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-116">Lists supported cloud appliance models and supported configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSupportedConfigurationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt; ListSupportedConfigurationsAsync (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt; ListSupportedConfigurationsAsync(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ListSupportedConfigurationsAsync(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSupportedConfigurationsAsync : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ListSupportedConfigurationsAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions/&lt;ListSupportedConfigurationsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.CloudApplianceConfiguration&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-118">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-118">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-119">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-119">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6e0f3-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-121">リストは、クラウド アプライアンス モデルがサポートされているしでサポートされる構成です。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-121">Lists supported cloud appliance models and supported configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provision">
      <MemberSignature Language="C#" Value="public static void Provision (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Provision(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.Provision(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Provision (operations As ICloudAppliancesOperations, parameters As CloudAppliance, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Provision : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.Provision (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-122">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6e0f3-123">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="6e0f3-123">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-124">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-124">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-125">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-125">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-126">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-126">Provisions cloud appliance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ProvisionAsync (this Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ProvisionAsync(class Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ProvisionAsync(Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ProvisionAsync : Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions.ProvisionAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.CloudAppliancesOperationsExtensions/&lt;ProvisionAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.ICloudAppliancesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6e0f3-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-127">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6e0f3-128">クラウド アプライアンス</span><span class="sxs-lookup"><span data-stu-id="6e0f3-128">The cloud appliance</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6e0f3-129">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-129">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="6e0f3-130">管理者名</span><span class="sxs-lookup"><span data-stu-id="6e0f3-130">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6e0f3-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6e0f3-132">クラウド アプライアンスをプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="6e0f3-132">Provisions cloud appliance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>