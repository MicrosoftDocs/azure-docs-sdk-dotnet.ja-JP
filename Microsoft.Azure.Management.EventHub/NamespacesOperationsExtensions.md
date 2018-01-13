<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ba871-101">NamespacesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="ba871-101">Extension methods for NamespacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.EHNamespace BeginCreateOrUpdate (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.EHNamespace BeginCreateOrUpdate(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As EHNamespace) As EHNamespace" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.EHNamespace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-103">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-104">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-104">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-105">名前空間リソースを作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-105">Parameters for creating a namespace resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-106">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-106">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-107">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-107">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-108">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-108">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-110">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-110">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-111">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-111">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-112">名前空間リソースを作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-112">Parameters for creating a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-114">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-114">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-115">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-115">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-116">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-116">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginDelete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-118">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-118">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-119">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-119">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-120">既存の名前空間を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-120">Deletes an existing namespace.</span></span> <span data-ttu-id="ba871-121">この操作には、名前空間の下の関連するすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ba871-121">This operation also removes all associated resources under the namespace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-123">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-123">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-124">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-124">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-126">既存の名前空間を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-126">Deletes an existing namespace.</span></span> <span data-ttu-id="ba871-127">この操作には、名前空間の下の関連するすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ba871-127">This operation also removes all associated resources under the namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.EventHub.INamespacesOperations,Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As INamespacesOperations, parameters As CheckNameAvailabilityParameter) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.EventHub.INamespacesOperations * Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter -&gt; Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CheckNameAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-128">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-129">パラメーターを指定された Namespace 名前の可用性を確認するには</span><span class="sxs-lookup"><span data-stu-id="ba871-129">Parameters to check availability of the given Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-130">Namespace 名前を使用できることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="ba871-130">Check the give Namespace name availability.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, class Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CheckNameAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.CheckNameAvailabilityParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-131">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-132">パラメーターを指定された Namespace 名前の可用性を確認するには</span><span class="sxs-lookup"><span data-stu-id="ba871-132">Parameters to check availability of the given Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-134">Namespace 名前を使用できることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="ba871-134">Check the give Namespace name availability.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.EHNamespace CreateOrUpdate (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.EHNamespace CreateOrUpdate(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As EHNamespace) As EHNamespace" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.EHNamespace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-136">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-136">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-137">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-137">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-138">名前空間リソースを作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-138">Parameters for creating a namespace resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-139">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-139">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-140">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-140">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-141">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-141">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-143">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-143">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-144">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-144">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-145">名前空間リソースを作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-145">Parameters for creating a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-147">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-147">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-148">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-148">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-149">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-149">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AuthorizationRule CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As AuthorizationRule) As AuthorizationRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.AuthorizationRule -&gt; Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-151">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-151">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-152">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-152">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-153">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-153">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-154">共有アクセス AuthorizationRule です。</span><span class="sxs-lookup"><span data-stu-id="ba871-154">The shared access AuthorizationRule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-155">作成するかの Namespace を AuthorizationRule を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-155">Creates or updates an AuthorizationRule for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.AuthorizationRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.AuthorizationRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-157">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-157">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-158">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-158">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-159">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-159">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-160">共有アクセス AuthorizationRule です。</span><span class="sxs-lookup"><span data-stu-id="ba871-160">The shared access AuthorizationRule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-162">作成するかの Namespace を AuthorizationRule を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-162">Creates or updates an AuthorizationRule for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Delete(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-164">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-164">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-165">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-165">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-166">既存の名前空間を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-166">Deletes an existing namespace.</span></span> <span data-ttu-id="ba871-167">この操作には、名前空間の下の関連するすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ba871-167">This operation also removes all associated resources under the namespace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-169">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-169">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-170">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-170">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-172">既存の名前空間を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-172">Deletes an existing namespace.</span></span> <span data-ttu-id="ba871-173">この操作には、名前空間の下の関連するすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="ba871-173">This operation also removes all associated resources under the namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-175">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-175">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-176">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-176">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-177">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-177">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-178">Namespace を AuthorizationRule を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-178">Deletes an AuthorizationRule for a Namespace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-180">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-180">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-181">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-181">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-182">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-182">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-184">Namespace を AuthorizationRule を削除します。</span><span class="sxs-lookup"><span data-stu-id="ba871-184">Deletes an AuthorizationRule for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.EHNamespace Get (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.EHNamespace Get(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Get(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As EHNamespace" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Get (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.EHNamespace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-186">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-186">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-187">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-187">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-188">指定した名前空間の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-188">Gets the description of the specified namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; GetAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; GetAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-190">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-190">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-191">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-191">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-193">指定した名前空間の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-193">Gets the description of the specified namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As AuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AuthorizationRule" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-195">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-195">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-196">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-196">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-197">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-197">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-198">ルールの名前では Namespace の AuthorizationRule を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-198">Gets an AuthorizationRule for a Namespace by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-200">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-200">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-201">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-201">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-202">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-202">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-204">ルールの名前では Namespace の AuthorizationRule を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-204">Gets an AuthorizationRule for a Namespace by rule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; List (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; List(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.List(Microsoft.Azure.Management.EventHub.INamespacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INamespacesOperations) As IPage(Of EHNamespace)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.EventHub.INamespacesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-205">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-206">リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-206">Lists all the available Namespaces within a subscription, irrespective of the resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-207">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-209">リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-209">Lists all the available Namespaces within a subscription, irrespective of the resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-211">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-211">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-212">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-212">The Namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-213">Namespace の承認規則の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-213">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-215">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-215">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-216">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-216">The Namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-218">Namespace の承認規則の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-218">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.EventHub.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-220">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-221">Namespace の承認規則の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-221">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.AuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-223">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-225">Namespace の承認規則の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-225">Gets a list of authorization rules for a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListByResourceGroup (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListByResourceGroup(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As INamespacesOperations, resourceGroupName As String) As IPage(Of EHNamespace)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.EventHub.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-227">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-227">Name of the resource group within the azure subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-228">リソース グループ内で使用できる名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-228">Lists the available Namespaces within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-230">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-230">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-232">リソース グループ内で使用できる名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-232">Lists the available Namespaces within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of EHNamespace)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.EventHub.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-233">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-234">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-234">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-235">リソース グループ内で使用できる名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-235">Lists the available Namespaces within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-236">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-237">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-237">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-239">リソース グループ内で使用できる名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-239">Lists the available Namespaces within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListKeys(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-240">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-241">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-241">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-242">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-242">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-243">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-243">The authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-244">Namespace のプライマリとセカンダリの接続文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-244">Gets the primary and secondary connection strings for the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-245">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-246">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-246">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-247">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-247">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-248">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-248">The authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-250">Namespace のプライマリとセカンダリの接続文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="ba871-250">Gets the primary and secondary connection strings for the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListNext (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; ListNext(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListNext(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INamespacesOperations, nextPageLink As String) As IPage(Of EHNamespace)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.EventHub.INamespacesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-251">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-252">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-252">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-253">リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-253">Lists all the available Namespaces within a subscription, irrespective of the resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-254">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ba871-255">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ba871-255">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-257">リソース グループに関係なく、サブスクリプション内で使用可能なすべての名前空間を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ba871-257">Lists all the available Namespaces within a subscription, irrespective of the resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.AccessKeys RegenerateKeys (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.AccessKeys RegenerateKeys(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, authorizationRuleName As String, parameters As RegenerateAccessKeyParameters) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters -&gt; Microsoft.Azure.Management.EventHub.Models.AccessKeys" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-258">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-259">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-259">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-260">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-260">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-261">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-261">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-262">接続文字列を再生成に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-262">Parameters required to regenerate the connection string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-263">指定された Namespace のプライマリまたはセカンダリの接続文字列を再生成します。</span><span class="sxs-lookup"><span data-stu-id="ba871-263">Regenerates the primary or secondary connection strings for the specified Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * string * Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-264">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-265">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-265">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-266">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-266">The Namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="ba871-267">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="ba871-267">The authorization rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-268">接続文字列を再生成に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-268">Parameters required to regenerate the connection string.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-270">指定された Namespace のプライマリまたはセカンダリの接続文字列を再生成します。</span><span class="sxs-lookup"><span data-stu-id="ba871-270">Regenerates the primary or secondary connection strings for the specified Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.EHNamespace Update (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.EHNamespace Update(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Update(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As INamespacesOperations, resourceGroupName As String, namespaceName As String, parameters As EHNamespace) As EHNamespace" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.Update (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.EHNamespace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-272">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-272">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-273">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-273">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-274">名前空間リソースを更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-274">Parameters for updating a namespace resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-275">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-275">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-276">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-276">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-277">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-277">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; UpdateAsync (this Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt; UpdateAsync(class Microsoft.Azure.Management.EventHub.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.EventHub.Models.EHNamespace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventHub.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.EHNamespace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventHub.INamespacesOperations * string * string * Microsoft.Azure.Management.EventHub.Models.EHNamespace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;" Usage="Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions.UpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.NamespacesOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.EHNamespace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ba871-278">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ba871-278">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ba871-279">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ba871-279">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="ba871-280">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="ba871-280">The Namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ba871-281">名前空間リソースを更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ba871-281">Parameters for updating a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ba871-282">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ba871-282">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ba871-283">作成するか、名前空間を更新します。</span><span class="sxs-lookup"><span data-stu-id="ba871-283">Creates or updates a namespace.</span></span> <span data-ttu-id="ba871-284">作成されると、この名前空間のリソース マニフェストは変更できません。</span><span class="sxs-lookup"><span data-stu-id="ba871-284">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="ba871-285">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="ba871-285">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>