<Type Name="IntegrationRuntimesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IntegrationRuntimesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IntegrationRuntimesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d646b-101">IntegrationRuntimesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="d646b-101">Extension methods for IntegrationRuntimesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse BeginStart (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse BeginStart(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStart(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStart (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-104">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-105">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-105">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-106">ManagedReserved 型統合ランタイムを起動します。</span><span class="sxs-lookup"><span data-stu-id="d646b-106">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStartAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;BeginStartAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-108">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-108">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-109">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-109">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-110">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-110">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-112">ManagedReserved 型統合ランタイムを起動します。</span><span class="sxs-lookup"><span data-stu-id="d646b-112">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStop(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStop (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-114">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-115">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-115">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-116">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-116">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-117">ManagedReserved 型統合ランタイムを停止します。</span><span class="sxs-lookup"><span data-stu-id="d646b-117">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.BeginStopAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;BeginStopAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-119">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-120">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-120">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-121">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-121">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-123">ManagedReserved 型統合ランタイムを停止します。</span><span class="sxs-lookup"><span data-stu-id="d646b-123">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, integrationRuntime As IntegrationRuntimeResource, Optional ifMatch As String = null) As IntegrationRuntimeResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, integrationRuntimeName, integrationRuntime, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="integrationRuntime" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-125">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-126">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-126">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-127">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-127">The integration runtime name.</span></span>
            </param>
        <param name="integrationRuntime">
            <span data-ttu-id="d646b-128">統合ランタイムのリソース定義します。</span><span class="sxs-lookup"><span data-stu-id="d646b-128">Integration runtime resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="d646b-129">統合ランタイム エンティティの ETag。</span><span class="sxs-lookup"><span data-stu-id="d646b-129">ETag of the integration runtime entity.</span></span> <span data-ttu-id="d646b-130">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-130">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-131">作成するか、統合ランタイムを更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-131">Creates or updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource integrationRuntime, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, integrationRuntime, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="integrationRuntime" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-133">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-133">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-134">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-134">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-135">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-135">The integration runtime name.</span></span>
            </param>
        <param name="integrationRuntime">
            <span data-ttu-id="d646b-136">統合ランタイムのリソース定義します。</span><span class="sxs-lookup"><span data-stu-id="d646b-136">Integration runtime resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="d646b-137">統合ランタイム エンティティの ETag。</span><span class="sxs-lookup"><span data-stu-id="d646b-137">ETag of the integration runtime entity.</span></span> <span data-ttu-id="d646b-138">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-138">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-140">作成するか、統合ランタイムを更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-140">Creates or updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-142">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-142">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-143">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-143">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-144">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-144">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-145">統合ランタイムを削除します。</span><span class="sxs-lookup"><span data-stu-id="d646b-145">Deletes an integration runtime.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-147">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-147">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-148">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-148">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-149">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-149">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-151">統合ランタイムを削除します。</span><span class="sxs-lookup"><span data-stu-id="d646b-151">Deletes an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource Get (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource Get(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Get (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-153">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-153">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-154">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-154">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-155">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-155">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-156">統合ランタイムを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-156">Gets an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-158">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-158">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-159">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-159">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-160">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-160">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-162">統合ランタイムを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-162">Gets an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo GetConnectionInfo (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo GetConnectionInfo(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfo(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetConnectionInfo (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeConnectionInfo" />
      <MemberSignature Language="F#" Value="static member GetConnectionInfo : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfo (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-164">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-164">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-165">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-165">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-166">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-166">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-167">オンプレミスの内部設置型のデータ ソースの資格情報を暗号化するための統合のランタイム接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-167">Gets the on-premises integration runtime connection information for encrypting the on-premises data source credentials.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt; GetConnectionInfoAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt; GetConnectionInfoAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfoAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetConnectionInfoAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetConnectionInfoAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetConnectionInfoAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-169">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-169">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-170">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-170">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-171">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-171">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-173">オンプレミスの内部設置型のデータ ソースの資格情報を暗号化するための統合のランタイム接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-173">Gets the on-premises integration runtime connection information for encrypting the on-premises data source credentials.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMonitoringData">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData GetMonitoringData (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData GetMonitoringData(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringData(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMonitoringData (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeMonitoringData" />
      <MemberSignature Language="F#" Value="static member GetMonitoringData : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringData (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-175">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-175">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-176">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-176">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-177">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-177">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-178">監視データをこの統合ランタイムの下にあるすべてのノードのモニターのデータを含む、統合ランタイムを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-178">Get the integration runtime monitoring data, which includes the monitor data for all the nodes under this integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMonitoringDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt; GetMonitoringDataAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt; GetMonitoringDataAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringDataAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMonitoringDataAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetMonitoringDataAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetMonitoringDataAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeMonitoringData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-180">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-180">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-181">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-181">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-182">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-182">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-184">監視データをこの統合ランタイムの下にあるすべてのノードのモニターのデータを含む、統合ランタイムを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-184">Get the integration runtime monitoring data, which includes the monitor data for all the nodes under this integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse GetStatus (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse GetStatus(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatus(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStatus (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member GetStatus : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatus (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-186">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-186">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-187">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-187">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-188">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-188">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-189">統合ランタイムの詳細なステータス情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-189">Gets detailed status information for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; GetStatusAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; GetStatusAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatusAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatusAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.GetStatusAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;GetStatusAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-191">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-191">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-192">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-192">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-193">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-193">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-195">統合ランタイムの詳細なステータス情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-195">Gets detailed status information for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys ListAuthKeys (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys ListAuthKeys(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeys(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeys (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeAuthKeys" />
      <MemberSignature Language="F#" Value="static member ListAuthKeys : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeys (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-197">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-197">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-198">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-198">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-199">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-199">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-200">統合ランタイムの認証キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-200">Retrieves the authentication keys for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; ListAuthKeysAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; ListAuthKeysAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeysAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthKeysAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListAuthKeysAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListAuthKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-202">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-202">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-203">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-203">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-204">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-204">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-206">統合ランタイムの認証キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d646b-206">Retrieves the authentication keys for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String) As IPage(Of IntegrationRuntimeResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-208">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-208">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-209">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-209">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-210">統合のランタイムを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d646b-210">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-211">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-211">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-212">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-212">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-213">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-213">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-215">統合のランタイムを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d646b-215">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IIntegrationRuntimesOperations, nextPageLink As String) As IPage(Of IntegrationRuntimeResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d646b-217">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d646b-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-218">統合のランタイムを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d646b-218">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d646b-220">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d646b-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-222">統合のランタイムを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d646b-222">Lists integration runtimes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys RegenerateAuthKey (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys RegenerateAuthKey(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKey(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKey (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, regenerateKeyParameters As IntegrationRuntimeRegenerateKeyParameters) As IntegrationRuntimeAuthKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKey : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKey (operations, resourceGroupName, factoryName, integrationRuntimeName, regenerateKeyParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="regenerateKeyParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-224">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-224">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-225">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-225">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-226">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-226">The integration runtime name.</span></span>
            </param>
        <param name="regenerateKeyParameters">
            <span data-ttu-id="d646b-227">統合ランタイム認証キーを再生成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d646b-227">The parameters for regenerating integration runtime authentication key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-228">認証キー、統合ランタイムを再生成します。</span><span class="sxs-lookup"><span data-stu-id="d646b-228">Regenerates the authentication key for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; RegenerateAuthKeyAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt; RegenerateAuthKeyAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters regenerateKeyParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKeyAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKeyAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RegenerateAuthKeyAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, regenerateKeyParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;RegenerateAuthKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeAuthKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="regenerateKeyParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRegenerateKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-230">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-230">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-231">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-231">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-232">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-232">The integration runtime name.</span></span>
            </param>
        <param name="regenerateKeyParameters">
            <span data-ttu-id="d646b-233">統合ランタイム認証キーを再生成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d646b-233">The parameters for regenerating integration runtime authentication key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-235">認証キー、統合ランタイムを再生成します。</span><span class="sxs-lookup"><span data-stu-id="d646b-235">Regenerates the authentication key for an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="public static void RemoveNode (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RemoveNode(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNode(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RemoveNode (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, removeNodeParameters As IntegrationRuntimeRemoveNodeRequest)" />
      <MemberSignature Language="F#" Value="static member RemoveNode : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNode (operations, resourceGroupName, factoryName, integrationRuntimeName, removeNodeParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="removeNodeParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-237">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-237">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-238">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-238">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-239">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-239">The integration runtime name.</span></span>
            </param>
        <param name="removeNodeParameters">
            <span data-ttu-id="d646b-240">統合ランタイムから削除するノードの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-240">The name of the node to be removed from an integration runtime.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-241">ノードは、統合ランタイムから削除します。</span><span class="sxs-lookup"><span data-stu-id="d646b-241">Remove a node from integration runtime.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveNodeAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveNodeAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest removeNodeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNodeAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveNodeAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.RemoveNodeAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, removeNodeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;RemoveNodeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="removeNodeParameters" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeRemoveNodeRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-243">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-243">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-244">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-244">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-245">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-245">The integration runtime name.</span></span>
            </param>
        <param name="removeNodeParameters">
            <span data-ttu-id="d646b-246">統合ランタイムから削除するノードの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-246">The name of the node to be removed from an integration runtime.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-248">ノードは、統合ランタイムから削除します。</span><span class="sxs-lookup"><span data-stu-id="d646b-248">Remove a node from integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Start (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Start(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Start(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String) As IntegrationRuntimeStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Start (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-250">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-250">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-251">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-251">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-252">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-252">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-253">ManagedReserved 型統合ランタイムを起動します。</span><span class="sxs-lookup"><span data-stu-id="d646b-253">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StartAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StartAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;StartAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-255">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-255">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-256">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-256">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-257">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-257">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-259">ManagedReserved 型統合ランタイムを起動します。</span><span class="sxs-lookup"><span data-stu-id="d646b-259">Starts a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Stop(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Stop (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-261">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-261">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-262">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-262">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-263">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-263">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-264">ManagedReserved 型統合ランタイムを停止します。</span><span class="sxs-lookup"><span data-stu-id="d646b-264">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StopAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.StopAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;StopAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-266">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-266">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-267">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-267">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-268">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-268">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-270">ManagedReserved 型統合ランタイムを停止します。</span><span class="sxs-lookup"><span data-stu-id="d646b-270">Stops a ManagedReserved type integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncCredentials">
      <MemberSignature Language="C#" Value="public static void SyncCredentials (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SyncCredentials(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentials(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SyncCredentials (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member SyncCredentials : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentials (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-272">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-272">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-273">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-273">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-274">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-274">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-275">強制的に、統合ランタイム ノードでの資格情報を同期するために、統合ランタイムと、このディスパッチャー ノードで利用できるすべての worker ノードの間で資格情報は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d646b-275">Force the integration runtime to synchronize credentials across integration runtime nodes, and this will override the credentials across all worker nodes with those available on the dispatcher node.</span></span> <span data-ttu-id="d646b-276">最新の資格情報のバックアップ ファイルがある場合手動で (推奨)、この API を直接使用するよりも自己ホスト型の統合ランタイム ノードにインポートする必要があります。</span><span class="sxs-lookup"><span data-stu-id="d646b-276">If you already have the latest credential backup file, you should manually import it (preferred) on any self-hosted integration runtime node than using this API directly.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SyncCredentialsAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SyncCredentialsAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentialsAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SyncCredentialsAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.SyncCredentialsAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;SyncCredentialsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-278">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-278">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-279">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-279">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-280">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-280">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-281">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-281">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-282">強制的に、統合ランタイム ノードでの資格情報を同期するために、統合ランタイムと、このディスパッチャー ノードで利用できるすべての worker ノードの間で資格情報は上書きされます。</span><span class="sxs-lookup"><span data-stu-id="d646b-282">Force the integration runtime to synchronize credentials across integration runtime nodes, and this will override the credentials across all worker nodes with those available on the dispatcher node.</span></span> <span data-ttu-id="d646b-283">最新の資格情報のバックアップ ファイルがある場合手動で (推奨)、この API を直接使用するよりも自己ホスト型の統合ランタイム ノードにインポートする必要があります。</span><span class="sxs-lookup"><span data-stu-id="d646b-283">If you already have the latest credential backup file, you should manually import it (preferred) on any self-hosted integration runtime node than using this API directly.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Update (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse Update(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Update(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Update (operations, resourceGroupName, factoryName, integrationRuntimeName, updateIntegrationRuntimeRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-284">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-284">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-285">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-285">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-286">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-286">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-287">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-287">The integration runtime name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeRequest">
            <span data-ttu-id="d646b-288">統合ランタイムを更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d646b-288">The parameters for updating an integration runtime.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-289">統合ランタイムを更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-289">Updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest updateIntegrationRuntimeRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpdateAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, updateIntegrationRuntimeRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-290">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-291">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-291">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-292">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-292">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-293">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-293">The integration runtime name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeRequest">
            <span data-ttu-id="d646b-294">統合ランタイムを更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d646b-294">The parameters for updating an integration runtime.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-295">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-295">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-296">統合ランタイムを更新します。</span><span class="sxs-lookup"><span data-stu-id="d646b-296">Updates an integration runtime.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upgrade">
      <MemberSignature Language="C#" Value="public static void Upgrade (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Upgrade(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Upgrade(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Upgrade (operations As IIntegrationRuntimesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String)" />
      <MemberSignature Language="F#" Value="static member Upgrade : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.Upgrade (operations, resourceGroupName, factoryName, integrationRuntimeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-297">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-297">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-298">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-298">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-299">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-299">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-300">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-300">The integration runtime name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-301">可用性の場合、最新バージョンに自己ホスト型の統合ランタイムをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="d646b-301">Upgrade self-hosted integration runtime to latest version if availably.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpgradeAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions.UpgradeAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimesOperationsExtensions/&lt;UpgradeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d646b-302">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d646b-302">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d646b-303">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="d646b-303">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="d646b-304">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="d646b-304">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="d646b-305">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="d646b-305">The integration runtime name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d646b-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d646b-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d646b-307">可用性の場合、最新バージョンに自己ホスト型の統合ランタイムをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="d646b-307">Upgrade self-hosted integration runtime to latest version if availably.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>