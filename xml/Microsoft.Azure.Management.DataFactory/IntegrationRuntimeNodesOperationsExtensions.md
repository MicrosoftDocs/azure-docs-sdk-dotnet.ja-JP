<Type Name="IntegrationRuntimeNodesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IntegrationRuntimeNodesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IntegrationRuntimeNodesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IntegrationRuntimeNodesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeNodesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e7310-101">IntegrationRuntimeNodesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e7310-101">Extension methods for IntegrationRuntimeNodesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IIntegrationRuntimeNodesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, nodeName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-104">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-105">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-105">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-106">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-106">The integration runtime node name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-107">自己ホスト型の統合ランタイム ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="e7310-107">Deletes a self-hosted integration runtime node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-109">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-109">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-110">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-110">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-111">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-111">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-112">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-112">The integration runtime node name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7310-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7310-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-114">自己ホスト型の統合ランタイム ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="e7310-114">Deletes a self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetIpAddress">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress GetIpAddress (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress GetIpAddress(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.GetIpAddress(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetIpAddress (operations As IIntegrationRuntimeNodesOperations, resourceGroupName As String, factoryName As String, integrationRuntimeName As String, nodeName As String) As IntegrationRuntimeNodeIpAddress" />
      <MemberSignature Language="F#" Value="static member GetIpAddress : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.GetIpAddress (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-116">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-116">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-117">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-117">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-118">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-118">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-119">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-119">The integration runtime node name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-120">自己ホスト型の統合ランタイム ノードの IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7310-120">Get the IP address of self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetIpAddressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt; GetIpAddressAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt; GetIpAddressAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.GetIpAddressAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetIpAddressAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.GetIpAddressAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions/&lt;GetIpAddressAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeNodeIpAddress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-122">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-122">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-123">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-123">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-124">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-124">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-125">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-125">The integration runtime node name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7310-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7310-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-127">自己ホスト型の統合ランタイム ノードの IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="e7310-127">Get the IP address of self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode Update (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode Update(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.Update(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest -&gt; Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.Update (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName, updateIntegrationRuntimeNodeRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeNodeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-129">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-129">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-130">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-130">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-131">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-131">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-132">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-132">The integration runtime node name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeNodeRequest">
            <span data-ttu-id="e7310-133">統合ランタイム ノードの更新のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e7310-133">The parameters for updating an integration runtime node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-134">自己ホスト型の統合ランタイム ノードを更新します。</span><span class="sxs-lookup"><span data-stu-id="e7310-134">Updates a self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations operations, string resourceGroupName, string factoryName, string integrationRuntimeName, string nodeName, class Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest updateIntegrationRuntimeNodeRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations * string * string * string * string * Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;" Usage="Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions.UpdateAsync (operations, resourceGroupName, factoryName, integrationRuntimeName, nodeName, updateIntegrationRuntimeNodeRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.IntegrationRuntimeNodesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="integrationRuntimeName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="updateIntegrationRuntimeNodeRequest" Type="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e7310-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e7310-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e7310-136">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="e7310-136">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="e7310-137">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7310-137">The factory name.</span></span>
            </param>
        <param name="integrationRuntimeName">
            <span data-ttu-id="e7310-138">統合ランタイムの名前。</span><span class="sxs-lookup"><span data-stu-id="e7310-138">The integration runtime name.</span></span>
            </param>
        <param name="nodeName">
            <span data-ttu-id="e7310-139">統合ランタイム ノード名です。</span><span class="sxs-lookup"><span data-stu-id="e7310-139">The integration runtime node name.</span></span>
            </param>
        <param name="updateIntegrationRuntimeNodeRequest">
            <span data-ttu-id="e7310-140">統合ランタイム ノードの更新のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e7310-140">The parameters for updating an integration runtime node.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e7310-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e7310-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e7310-142">自己ホスト型の統合ランタイム ノードを更新します。</span><span class="sxs-lookup"><span data-stu-id="e7310-142">Updates a self-hosted integration runtime node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>