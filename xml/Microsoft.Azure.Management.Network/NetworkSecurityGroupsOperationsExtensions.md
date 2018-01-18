<Type Name="NetworkSecurityGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkSecurityGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkSecurityGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="19397-101">NetworkSecurityGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="19397-101">Extension methods for NetworkSecurityGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As NetworkSecurityGroup) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-103">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-104">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-104">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-105">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-105">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-106">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-106">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-108">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-109">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-109">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-110">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-110">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-112">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-112">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName, networkSecurityGroupName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-114">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-115">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-115">The name of the network security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-116">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="19397-116">Deletes the specified network security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-118">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-119">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-119">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-121">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="19397-121">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginUpdateTags (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup BeginUpdateTags(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As TagsObject) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-123">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-124">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-124">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-125">ネットワーク セキュリティ グループのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-125">Parameters supplied to update network security group tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-126">ネットワーク セキュリティ グループ タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-126">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-128">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-129">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-129">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-130">ネットワーク セキュリティ グループのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-130">Parameters supplied to update network security group tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-132">ネットワーク セキュリティ グループ タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-132">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup CreateOrUpdate (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup CreateOrUpdate(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As NetworkSecurityGroup) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-134">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-135">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-135">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-136">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-136">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-137">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-137">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-139">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-140">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-140">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-141">作成または更新ネットワーク セキュリティ グループ操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-141">Parameters supplied to the create or update network security group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-143">作成するか、指定されたリソース グループでのネットワーク セキュリティ グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-143">Creates or updates a network security group in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Delete (operations, resourceGroupName, networkSecurityGroupName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-145">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-146">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-146">The name of the network security group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-147">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="19397-147">Deletes the specified network security group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkSecurityGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-149">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-150">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-150">The name of the network security group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-152">指定されたネットワーク セキュリティ グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="19397-152">Deletes the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup Get (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup Get(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, Optional expand As String = null) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.Get (operations, resourceGroupName, networkSecurityGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-154">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-155">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-155">The name of the network security group.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="19397-156">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="19397-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-157">指定されたネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-157">Gets the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; GetAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; GetAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, networkSecurityGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-159">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-160">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-160">The name of the network security group.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="19397-161">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="19397-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-163">指定されたネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-163">Gets the specified network security group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; List (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; List(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.List(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INetworkSecurityGroupsOperations, resourceGroupName As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-165">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-166">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-166">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAll (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAll(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As INetworkSecurityGroupsOperations) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-167">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-168">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-168">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-169">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-171">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-171">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAllNext (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListAllNext(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As INetworkSecurityGroupsOperations, nextPageLink As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="19397-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="19397-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-174">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-174">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAllNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="19397-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="19397-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-178">サブスクリプションのすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-178">Gets all network security groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-180">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-180">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-182">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-182">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListNext (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; ListNext(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INetworkSecurityGroupsOperations, nextPageLink As String) As IPage(Of NetworkSecurityGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="19397-184">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="19397-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-185">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-185">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="19397-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="19397-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-189">リソース グループ内のすべてのネットワーク セキュリティ グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="19397-189">Gets all network security groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup UpdateTags (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup UpdateTags(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As INetworkSecurityGroupsOperations, resourceGroupName As String, networkSecurityGroupName As String, parameters As TagsObject) As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTags (operations, resourceGroupName, networkSecurityGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-191">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-192">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-192">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-193">ネットワーク セキュリティ グループのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-193">Parameters supplied to update network security group tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-194">ネットワーク セキュリティ グループ タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-194">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations operations, string resourceGroupName, string networkSecurityGroupName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;" Usage="Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, networkSecurityGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkSecurityGroupsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkSecurityGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkSecurityGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="19397-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="19397-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="19397-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-196">The name of the resource group.</span></span>
            </param>
        <param name="networkSecurityGroupName">
            <span data-ttu-id="19397-197">ネットワーク セキュリティ グループの名前。</span><span class="sxs-lookup"><span data-stu-id="19397-197">The name of the network security group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19397-198">ネットワーク セキュリティ グループのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="19397-198">Parameters supplied to update network security group tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19397-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19397-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19397-200">ネットワーク セキュリティ グループ タグを更新します。</span><span class="sxs-lookup"><span data-stu-id="19397-200">Updates a network security group tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>