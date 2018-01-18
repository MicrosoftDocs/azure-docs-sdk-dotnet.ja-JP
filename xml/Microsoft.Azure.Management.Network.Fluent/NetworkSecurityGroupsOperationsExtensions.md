<Type Name="NetworkSecurityGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkSecurityGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="3630f-101">NetworkSecurityGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3630f-101">Extension methods for NetworkSecurityGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-103">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="3630f-104">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-104">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3630f-105">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3630f-105">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-107">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="3630f-107">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-109">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="3630f-110">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-110">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-112">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="3630f-112">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-114">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="3630f-115">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-115">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3630f-116">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3630f-116">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-118">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="3630f-118">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-120">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="3630f-121">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-121">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-123">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="3630f-123">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-125">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="3630f-126">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-126">The name of the network security group.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3630f-127">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="3630f-127">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-129">指定されたネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="3630f-129">Gets the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-130">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-132">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="3630f-132">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3630f-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3630f-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-136">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="3630f-136">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3630f-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3630f-138">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-140">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="3630f-140">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkSecurityGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkSecurityGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3630f-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3630f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3630f-142">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3630f-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3630f-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3630f-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3630f-144">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="3630f-144">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>