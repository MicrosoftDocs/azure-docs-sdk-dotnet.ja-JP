<Type Name="ReplicationsOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2e6cd-101">ReplicationsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-101">Extension methods for ReplicationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginCreate (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginCreate(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, location As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreate (operations, resourceGroupName, registryName, replicationName, location, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-103">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-103">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-104">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-104">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-105">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-105">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2e6cd-106">リソースの場所です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-106">The location of the resource.</span></span> <span data-ttu-id="2e6cd-107">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-107">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-108">リソースのタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-108">The tags of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-109">指定したパラメーターにコンテナー レジストリの複製を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-109">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginCreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginCreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, registryName, replicationName, location, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-111">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-111">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-112">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-112">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-113">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-113">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2e6cd-114">リソースの場所です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-114">The location of the resource.</span></span> <span data-ttu-id="2e6cd-115">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-115">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-116">リソースのタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-116">The tags of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-118">指定したパラメーターにコンテナー レジストリの複製を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-118">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDelete (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-120">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-120">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-121">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-121">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-122">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-122">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-123">コンテナー レジストリからレプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-123">Deletes a replication from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-125">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-125">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-126">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-126">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-127">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-127">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-129">コンテナー レジストリからレプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-129">Deletes a replication from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginUpdate (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication BeginUpdate(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdate (operations, resourceGroupName, registryName, replicationName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-131">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-131">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-132">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-132">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-133">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-133">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-134">レプリケーション用のタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-134">The tags for the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-135">指定したパラメーターにコンテナー レジストリにレプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-135">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, registryName, replicationName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-137">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-137">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-138">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-138">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-139">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-139">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-140">レプリケーション用のタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-140">The tags for the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-142">指定したパラメーターにコンテナー レジストリにレプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-142">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Create (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Create(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Create(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, location As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Create (operations, resourceGroupName, registryName, replicationName, location, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-144">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-144">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-145">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-145">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-146">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-146">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2e6cd-147">リソースの場所です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-147">The location of the resource.</span></span> <span data-ttu-id="2e6cd-148">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-148">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-149">リソースのタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-149">The tags of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-150">指定したパラメーターにコンテナー レジストリの複製を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-150">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; CreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; CreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.CreateAsync (operations, resourceGroupName, registryName, replicationName, location, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-152">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-152">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-153">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-153">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-154">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-154">The name of the replication.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="2e6cd-155">リソースの場所です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-155">The location of the resource.</span></span> <span data-ttu-id="2e6cd-156">これは、リソースを作成した後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-156">This cannot be changed after the resource is created.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-157">リソースのタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-157">The tags of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-159">指定したパラメーターにコンテナー レジストリの複製を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-159">Creates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Delete (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-161">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-161">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-162">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-162">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-163">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-163">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-164">コンテナー レジストリからレプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-164">Deletes a replication from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.DeleteAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-166">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-166">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-167">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-167">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-168">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-168">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-170">コンテナー レジストリからレプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-170">Deletes a replication from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Get (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Get(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Get(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String) As Replication" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Get (operations, resourceGroupName, registryName, replicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-172">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-172">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-173">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-173">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-174">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-174">The name of the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-175">指定したレプリケーションのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-175">Gets the properties of the specified replication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; GetAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; GetAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.GetAsync (operations, resourceGroupName, registryName, replicationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-177">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-177">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-178">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-178">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-179">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-179">The name of the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-181">指定したレプリケーションのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-181">Gets the properties of the specified replication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; List (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; List(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.List(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IReplicationsOperations, resourceGroupName As String, registryName As String) As IPage(Of Replication)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.List (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-183">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-183">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-184">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-184">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-185">指定したコンテナー レジストリに対するすべてのレプリケーションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-185">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-187">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-187">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-188">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-188">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-190">指定したコンテナー レジストリに対するすべてのレプリケーションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-190">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; ListNext (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; ListNext(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IReplicationsOperations, nextPageLink As String) As IPage(Of Replication)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2e6cd-192">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-193">指定したコンテナー レジストリに対するすべてのレプリケーションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-193">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2e6cd-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-197">指定したコンテナー レジストリに対するすべてのレプリケーションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-197">Lists all the replications for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Replication Update (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Replication Update(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Update(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IReplicationsOperations, resourceGroupName As String, registryName As String, replicationName As String, Optional tags As IDictionary(Of String, String) = null) As Replication" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Replication" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.Update (operations, resourceGroupName, registryName, replicationName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Replication</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-199">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-199">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-200">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-200">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-201">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-201">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-202">レプリケーション用のタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-202">The tags for the replication.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-203">指定したパラメーターにコンテナー レジストリにレプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-203">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; UpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt; UpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations operations, string resourceGroupName, string registryName, string replicationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions.UpdateAsync (operations, resourceGroupName, registryName, replicationName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.ReplicationsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Replication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IReplicationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="replicationName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e6cd-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e6cd-205">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-205">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="2e6cd-206">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-206">The name of the container registry.</span></span>
            </param>
        <param name="replicationName">
            <span data-ttu-id="2e6cd-207">レプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-207">The name of the replication.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="2e6cd-208">レプリケーション用のタグ。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-208">The tags for the replication.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e6cd-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e6cd-210">指定したパラメーターにコンテナー レジストリにレプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="2e6cd-210">Updates a replication for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>