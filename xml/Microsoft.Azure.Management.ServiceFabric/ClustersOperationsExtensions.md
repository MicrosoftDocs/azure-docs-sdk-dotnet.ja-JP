<Type Name="ClustersOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ClustersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ClustersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ClustersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ClustersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="34bc4-101">ClustersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="34bc4-101">Extension methods for ClustersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceFabric.Models.Cluster BeginCreate (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceFabric.Models.Cluster BeginCreate(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.Cluster)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As Cluster) As Cluster" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.Cluster -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginCreate (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.Cluster" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-103">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-103">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-104">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-104">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-105">Put 要求</span><span class="sxs-lookup"><span data-stu-id="34bc4-105">Put Request</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-106">クラスター リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-106">Create cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; BeginCreateAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; BeginCreateAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.Cluster,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.Cluster * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;BeginCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.Cluster" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-108">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-108">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-109">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-109">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-110">Put 要求</span><span class="sxs-lookup"><span data-stu-id="34bc4-110">Put Request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-112">クラスター リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-112">Create cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceFabric.Models.Cluster BeginUpdate (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceFabric.Models.Cluster BeginUpdate(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterUpdateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginUpdate (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-114">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-114">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-115">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-115">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-116">クラスター構成を更新するために使用されるプロパティの名前とプロパティの値を含むパラメーター</span><span class="sxs-lookup"><span data-stu-id="34bc4-116">The parameters which contains the property value and property name which used to update the cluster configuration</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-117">クラスターの更新の構成</span><span class="sxs-lookup"><span data-stu-id="34bc4-117">Update cluster configuration</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-119">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-119">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-120">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-120">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-121">クラスター構成を更新するために使用されるプロパティの名前とプロパティの値を含むパラメーター</span><span class="sxs-lookup"><span data-stu-id="34bc4-121">The parameters which contains the property value and property name which used to update the cluster configuration</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-123">クラスターの更新の構成</span><span class="sxs-lookup"><span data-stu-id="34bc4-123">Update cluster configuration</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceFabric.Models.Cluster Create (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceFabric.Models.Cluster Create(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Create(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.Cluster)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As Cluster) As Cluster" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.Cluster -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.Cluster" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-125">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-125">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-126">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-126">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-127">Put 要求</span><span class="sxs-lookup"><span data-stu-id="34bc4-127">Put Request</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-128">クラスター リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-128">Create cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; CreateAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; CreateAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.Cluster parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.Cluster,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.Cluster * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;CreateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.Cluster" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-130">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-130">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-131">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-131">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-132">Put 要求</span><span class="sxs-lookup"><span data-stu-id="34bc4-132">Put Request</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-134">クラスター リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-134">Create cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Delete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-136">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-136">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-137">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-137">The name of the cluster resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-138">クラスター リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-138">Delete cluster resource</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.DeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-140">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-140">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-141">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-141">The name of the cluster resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-143">クラスター リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-143">Delete cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceFabric.Models.Cluster Get (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceFabric.Models.Cluster Get(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Get(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As Cluster" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Get (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-145">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-145">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-146">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-146">The name of the cluster resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-147">クラスター リソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-147">Get cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; GetAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; GetAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.GetAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-149">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-149">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-150">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-150">The name of the cluster resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-152">クラスター リソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="34bc4-152">Get cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; List (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; List(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.List(Microsoft.Azure.Management.ServiceFabric.IClustersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IClustersOperations) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ServiceFabric.IClustersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-153">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-154">クラスター リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-154">List cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-155">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-157">クラスター リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-157">List cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListByResourceGroup (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListByResourceGroup(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IClustersOperations, resourceGroupName As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-159">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-159">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-160">クラスター リソースでリソース グループの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-160">List cluster resource by resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-162">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-162">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-164">クラスター リソースでリソース グループの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-164">List cluster resource by resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-165">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="34bc4-166">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="34bc4-166">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-167">クラスター リソースでリソース グループの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-167">List cluster resource by resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-168">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="34bc4-169">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="34bc4-169">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-171">クラスター リソースでリソース グループの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-171">List cluster resource by resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListNext (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; ListNext(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListNext(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="34bc4-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="34bc4-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-174">クラスター リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-174">List cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="34bc4-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="34bc4-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-178">クラスター リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="34bc4-178">List cluster resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceFabric.Models.Cluster Update (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceFabric.Models.Cluster Update(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Update(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterUpdateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.Update (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-180">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-180">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-181">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-181">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-182">クラスター構成を更新するために使用されるプロパティの名前とプロパティの値を含むパラメーター</span><span class="sxs-lookup"><span data-stu-id="34bc4-182">The parameters which contains the property value and property name which used to update the cluster configuration</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-183">クラスターの更新の構成</span><span class="sxs-lookup"><span data-stu-id="34bc4-183">Update cluster configuration</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; UpdateAsync (this Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt; UpdateAsync(class Microsoft.Azure.Management.ServiceFabric.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ServiceFabric.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ServiceFabric.IClustersOperations * string * string * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions.UpdateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceFabric.ClustersOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceFabric.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceFabric.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="34bc4-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="34bc4-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="34bc4-185">リソースの名前のリソースが属しているグループまたは作成</span><span class="sxs-lookup"><span data-stu-id="34bc4-185">The name of the resource group to which the resource belongs or get created</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="34bc4-186">クラスター リソースの名前</span><span class="sxs-lookup"><span data-stu-id="34bc4-186">The name of the cluster resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34bc4-187">クラスター構成を更新するために使用されるプロパティの名前とプロパティの値を含むパラメーター</span><span class="sxs-lookup"><span data-stu-id="34bc4-187">The parameters which contains the property value and property name which used to update the cluster configuration</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34bc4-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34bc4-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34bc4-189">クラスターの更新の構成</span><span class="sxs-lookup"><span data-stu-id="34bc4-189">Update cluster configuration</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>