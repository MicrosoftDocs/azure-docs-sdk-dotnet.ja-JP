<Type Name="ExpressRouteCircuitsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="15bee-101">ExpressRouteCircuitsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="15bee-101">Extension methods for ExpressRouteCircuitsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As ExpressRouteCircuit) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-104">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-104">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-105">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-105">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-106">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-106">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-108">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-109">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-109">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-110">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-110">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-112">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-112">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDelete (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-114">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-115">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-115">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-116">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="15bee-116">Deletes the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-118">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-119">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-119">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-121">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="15bee-121">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult BeginListArpTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult BeginListArpTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListArpTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsArpTableListResult" />
      <MemberSignature Language="F#" Value="static member BeginListArpTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-123">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-124">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-124">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-125">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-125">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-126">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-126">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-127">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-127">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; BeginListArpTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; BeginListArpTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListArpTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListArpTableAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-129">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-130">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-130">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-131">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-131">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-132">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-132">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-134">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-134">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult BeginListRoutesTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult BeginListRoutesTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListRoutesTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableListResult" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-136">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-137">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-137">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-138">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-138">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-139">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-139">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-140">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-140">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; BeginListRoutesTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; BeginListRoutesTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-142">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-143">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-143">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-144">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-144">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-145">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-145">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-147">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-147">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult BeginListRoutesTableSummary (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult BeginListRoutesTableSummary(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummary(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListRoutesTableSummary (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableSummaryListResult" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummary : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummary (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-149">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-150">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-150">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-151">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-151">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-152">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-152">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-153">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-153">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; BeginListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; BeginListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableSummaryAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-155">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-155">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-156">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-156">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-157">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-157">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-158">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-158">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-160">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-160">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginUpdateTags (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginUpdateTags(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As TagsObject) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-162">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-162">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-163">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-163">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-164">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-164">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-165">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-165">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-167">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-167">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-168">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-168">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-169">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-169">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-171">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-171">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit CreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit CreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As ExpressRouteCircuit) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-173">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-174">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-174">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-175">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-175">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-176">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-176">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-178">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-179">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-179">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-180">作成または更新の express route 回線操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-180">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-182">作成するか、express route 回線を更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-182">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Delete (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-184">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-185">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-185">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-186">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="15bee-186">Deletes the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-188">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-188">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-189">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-189">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-191">指定の express route 回線を削除します。</span><span class="sxs-lookup"><span data-stu-id="15bee-191">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit Get (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit Get(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Get (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-193">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-193">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-194">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-194">The name of express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-195">指定の express route 回線に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-195">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; GetAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; GetAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-197">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-197">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-198">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-198">The name of express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-200">指定の express route 回線に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-200">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetPeeringStats (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetPeeringStats(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStats(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPeeringStats (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String) As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="static member GetPeeringStats : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStats (operations, resourceGroupName, circuitName, peeringName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-202">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-203">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-203">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-204">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-204">The name of the peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-205">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-205">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetPeeringStatsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetPeeringStatsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPeeringStatsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetPeeringStatsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-207">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-207">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-208">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-208">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-209">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-209">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-211">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-211">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetStats (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetStats(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStats(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStats (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String) As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="static member GetStats : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStats (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-213">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-213">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-214">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-214">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-215">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-215">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetStatsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetStatsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetStatsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-217">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-217">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-218">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-218">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-220">リソース グループで、express route 回線からすべての統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-220">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; List (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; List(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.List(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IExpressRouteCircuitsOperations, resourceGroupName As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-222">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-222">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-223">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-223">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAll (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAll(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IExpressRouteCircuitsOperations) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-224">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-225">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-225">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-226">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-228">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-228">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAllNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAllNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IExpressRouteCircuitsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-229">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15bee-230">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="15bee-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-231">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-231">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-232">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-232">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15bee-233">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="15bee-233">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-235">サブスクリプションのすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-235">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult ListArpTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult ListArpTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListArpTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsArpTableListResult" />
      <MemberSignature Language="F#" Value="static member ListArpTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-237">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-237">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-238">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-238">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-239">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-239">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-240">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-240">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-241">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-241">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; ListArpTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; ListArpTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListArpTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListArpTableAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-243">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-243">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-244">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-244">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-245">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-245">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-246">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-246">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-248">リソース グループ内の express route 回線に関連付けられている現在の提供の ARP テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-248">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-250">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-250">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-252">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-252">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IExpressRouteCircuitsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-253">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15bee-254">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="15bee-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-255">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-255">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="15bee-257">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="15bee-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-259">リソース グループ内のすべての express route 回線を取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-259">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult ListRoutesTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult ListRoutesTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableListResult" />
      <MemberSignature Language="F#" Value="static member ListRoutesTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-261">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-261">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-262">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-262">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-263">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-263">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-264">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-264">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-265">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-265">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; ListRoutesTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; ListRoutesTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-266">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-267">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-267">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-268">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-268">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-269">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-269">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-270">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-270">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-272">リソース グループ内の express route 回線に関連付けられている現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-272">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult ListRoutesTableSummary (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult ListRoutesTableSummary(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummary(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesTableSummary (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableSummaryListResult" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummary : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummary (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-274">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-274">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-275">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-275">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-276">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-276">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-277">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-277">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-278">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-278">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; ListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; ListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableSummaryAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-279">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-279">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-280">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-280">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-281">Express route 回線の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-281">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="15bee-282">ピアリングの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-282">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="15bee-283">デバイスのパス。</span><span class="sxs-lookup"><span data-stu-id="15bee-283">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-284">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-285">リソース グループ内の express route 回線に関連付けられている概要現在アドバタイズされたルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="15bee-285">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit UpdateTags (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit UpdateTags(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As TagsObject) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTags (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-286">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-286">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-287">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-287">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-288">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-288">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-289">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-289">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-290">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-290">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="15bee-291">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="15bee-291">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="15bee-292">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-292">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="15bee-293">回路の名前。</span><span class="sxs-lookup"><span data-stu-id="15bee-293">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15bee-294">Express route 回線タグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="15bee-294">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15bee-295">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="15bee-295">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15bee-296">Express route 回線タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="15bee-296">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>