<Type Name="TriggersOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TriggersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TriggersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TriggersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TriggersOperationsExtensions = class" />
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
            <span data-ttu-id="9c2c5-101">TriggersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-101">Extension methods for TriggersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStart(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStart (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-104">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-105">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-105">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-106">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-106">Starts a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStartAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;BeginStartAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-108">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-108">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-109">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-109">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-110">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-110">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-112">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-112">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStop(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStop (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-114">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-115">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-115">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-116">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-116">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-117">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-117">Stops a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.BeginStopAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;BeginStopAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-119">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-120">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-120">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-121">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-121">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-123">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-123">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.TriggerResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.TriggerResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, class Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.TriggerResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String, trigger As TriggerResource, Optional ifMatch As String = null) As TriggerResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.TriggerResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerResource" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, triggerName, trigger, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-125">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-126">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-126">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-127">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-127">The trigger name.</span></span>
            </param>
        <param name="trigger">
            <span data-ttu-id="9c2c5-128">リソース定義をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-128">Trigger resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="9c2c5-129">トリガーのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-129">ETag of the trigger entity.</span></span>  <span data-ttu-id="9c2c5-130">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-130">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-131">作成するか、トリガーを更新します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-131">Creates or updates a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, class Microsoft.Azure.Management.DataFactory.Models.TriggerResource trigger, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.TriggerResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.TriggerResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, triggerName, trigger, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-133">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-133">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-134">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-134">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-135">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-135">The trigger name.</span></span>
            </param>
        <param name="trigger">
            <span data-ttu-id="9c2c5-136">リソース定義をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-136">Trigger resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="9c2c5-137">トリガーのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-137">ETag of the trigger entity.</span></span>  <span data-ttu-id="9c2c5-138">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-138">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-140">作成するか、トリガーを更新します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-140">Creates or updates a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Delete (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-142">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-142">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-143">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-143">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-144">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-144">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-145">トリガーを削除します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-145">Deletes a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-147">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-147">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-148">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-148">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-149">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-149">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-151">トリガーを削除します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-151">Deletes a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.TriggerResource Get (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.TriggerResource Get(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String) As TriggerResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.TriggerResource" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Get (operations, resourceGroupName, factoryName, triggerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-153">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-153">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-154">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-154">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-155">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-155">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-156">トリガーを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-156">Gets a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-158">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-158">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-159">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-159">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-160">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-160">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-162">トリガーを取得します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-162">Gets a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As ITriggersOperations, resourceGroupName As String, factoryName As String) As IPage(Of TriggerResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-164">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-164">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-165">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-165">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-166">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-166">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-168">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-168">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-169">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-169">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-171">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-171">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As ITriggersOperations, nextPageLink As String) As IPage(Of TriggerResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c2c5-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-174">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-174">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c2c5-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-178">トリガーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-178">Lists triggers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRuns">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRuns (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, DateTime startTime, DateTime endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRuns(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.DateTime startTime, valuetype System.DateTime endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRuns(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.DateTime,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRuns (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String, startTime As DateTime, endTime As DateTime) As IPage(Of TriggerRun)" />
      <MemberSignature Language="F#" Value="static member ListRuns : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * DateTime * DateTime -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRuns (operations, resourceGroupName, factoryName, triggerName, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-180">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-180">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-181">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-181">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-182">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-182">The trigger name.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="9c2c5-183">トリガーの実行の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-183">Start time for trigger runs.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="9c2c5-184">トリガーの終了時刻を実行します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-184">End time for trigger runs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-185">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-185">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, DateTime startTime, DateTime endTime, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.DateTime startTime, valuetype System.DateTime endTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.DateTime,System.DateTime,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRunsAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * DateTime * DateTime * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsAsync (operations, resourceGroupName, factoryName, triggerName, startTime, endTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListRunsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-187">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-187">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-188">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-188">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-189">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-189">The trigger name.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="9c2c5-190">トリガーの実行の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-190">Start time for trigger runs.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="9c2c5-191">トリガーの終了時刻を実行します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-191">End time for trigger runs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-193">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-193">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRunsNext (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt; ListRunsNext(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNext(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRunsNext (operations As ITriggersOperations, nextPageLink As String) As IPage(Of TriggerRun)" />
      <MemberSignature Language="F#" Value="static member ListRunsNext : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c2c5-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-196">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-196">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRunsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsNextAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt; ListRunsNextAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNextAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRunsNextAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.ListRunsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;ListRunsNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.TriggerRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9c2c5-198">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-200">一覧のトリガーが実行されます。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-200">List trigger runs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Start(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Start (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-202">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-202">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-203">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-203">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-204">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-204">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-205">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-205">Starts a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StartAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StartAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;StartAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-207">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-207">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-208">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-208">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-209">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-209">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-211">トリガーを起動します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-211">Starts a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Stop(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As ITriggersOperations, resourceGroupName As String, factoryName As String, triggerName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.Stop (operations, resourceGroupName, factoryName, triggerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-213">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-213">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-214">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-214">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-215">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-215">The trigger name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-216">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-216">Stops a trigger.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.DataFactory.ITriggersOperations operations, string resourceGroupName, string factoryName, string triggerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StopAsync(Microsoft.Azure.Management.DataFactory.ITriggersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.DataFactory.ITriggersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions.StopAsync (operations, resourceGroupName, factoryName, triggerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.TriggersOperationsExtensions/&lt;StopAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.ITriggersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="triggerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c2c5-217">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9c2c5-218">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-218">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="9c2c5-219">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-219">The factory name.</span></span>
            </param>
        <param name="triggerName">
            <span data-ttu-id="9c2c5-220">トリガーの名前です。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-220">The trigger name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c2c5-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c2c5-222">トリガーを停止します。</span><span class="sxs-lookup"><span data-stu-id="9c2c5-222">Stops a trigger.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>