<Type Name="ExpressRouteCircuitsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9097d-101">ExpressRouteCircuitsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9097d-101">Extension methods for ExpressRouteCircuitsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-104">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-104">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9097d-105">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="9097d-105">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-107">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="9097d-107">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-109">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-110">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-110">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-112">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="9097d-112">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; BeginListArpTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; BeginListArpTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListArpTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListArpTableAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-114">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-115">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-115">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-116">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-116">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-117">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-117">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-119">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-119">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; BeginListRoutesTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; BeginListRoutesTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-121">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-122">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-122">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-123">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-123">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-124">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-124">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-126">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-126">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; BeginListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; BeginListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableSummaryAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-128">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-129">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-129">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-130">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-130">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-131">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-131">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-133">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-133">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-135">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-136">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-136">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9097d-137">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="9097d-137">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-139">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="9097d-139">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-141">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-142">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-142">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-144">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="9097d-144">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-146">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-146">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-147">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-147">The name of express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-149">指定の express route 回線に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-149">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetPeeringStatsAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetPeeringStatsAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPeeringStatsAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetPeeringStatsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-151">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-152">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-152">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-153">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-153">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-155">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-155">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetStatsAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetStatsAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetStatsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-157">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-158">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-158">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-160">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-160">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-161">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-163">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-163">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-164">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9097d-165">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9097d-165">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-167">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-167">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; ListArpTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; ListArpTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListArpTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListArpTableAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-169">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-170">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-170">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-171">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-171">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-172">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-172">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-174">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-174">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-176">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-176">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-178">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-178">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9097d-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9097d-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-182">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-182">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; ListRoutesTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; ListRoutesTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-184">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-185">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-185">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-186">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-186">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-187">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-187">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-189">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-189">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; ListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; ListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableSummaryAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9097d-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9097d-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9097d-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-191">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="9097d-192">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-192">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="9097d-193">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="9097d-193">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="9097d-194">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="9097d-194">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9097d-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9097d-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9097d-196">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="9097d-196">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>