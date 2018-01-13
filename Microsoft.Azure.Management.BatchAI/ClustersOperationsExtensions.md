<Type Name="ClustersOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ClustersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ClustersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ClustersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ClustersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8665d-101">ClustersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8665d-101">Extension methods for ClustersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster BeginCreate (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster BeginCreate(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreate (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-104">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-104">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-105">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-105">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-106">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-106">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-107">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-107">The parameters to provide for cluster creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-108">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="8665d-108">Adds a cluster.</span></span> <span data-ttu-id="8665d-109">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="8665d-109">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="8665d-110">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8665d-110">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;BeginCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-112">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-112">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-113">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-113">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-114">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-114">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-115">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-115">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-116">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-116">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-118">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="8665d-118">Adds a cluster.</span></span> <span data-ttu-id="8665d-119">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="8665d-119">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="8665d-120">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8665d-120">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDelete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-122">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-123">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-123">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-124">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-124">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-125">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-125">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-126">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="8665d-126">Deletes a Cluster.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-128">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-128">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-129">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-129">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-130">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-130">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-131">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-131">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-133">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="8665d-133">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Create (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Create(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-135">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-135">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-136">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-136">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-137">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-137">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-138">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-138">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-139">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-139">The parameters to provide for cluster creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-140">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="8665d-140">Adds a cluster.</span></span> <span data-ttu-id="8665d-141">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="8665d-141">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="8665d-142">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8665d-142">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-145">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-145">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-146">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-146">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-147">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-147">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-148">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-148">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-150">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="8665d-150">Adds a cluster.</span></span> <span data-ttu-id="8665d-151">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="8665d-151">A cluster is a collection of compute nodes.</span></span> <span data-ttu-id="8665d-152">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8665d-152">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Delete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-154">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-154">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-155">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-155">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-156">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-156">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-157">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-157">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-158">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="8665d-158">Deletes a Cluster.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.DeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-160">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-160">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-161">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-161">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-162">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-162">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-163">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-163">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-165">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="8665d-165">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Get (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Get(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As Cluster" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Get (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-167">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-167">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-168">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-168">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-169">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-169">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-170">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-170">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-171">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-171">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.GetAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-173">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-173">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-174">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-174">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-175">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-175">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-176">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-176">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-178">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-178">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; List (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; List(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IClustersOperations,Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IClustersOperations * Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.List (operations, clustersListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="clustersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-179">The operations group for this extension method.</span></span>
            </param>
        <param name="clustersListOptions">
            <span data-ttu-id="8665d-180">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8665d-180">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-181">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-181">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListAsync (operations, clustersListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="clustersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-182">The operations group for this extension method.</span></span>
            </param>
        <param name="clustersListOptions">
            <span data-ttu-id="8665d-183">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8665d-183">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-185">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-185">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, clustersListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clustersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-187">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clustersListByResourceGroupOptions">
            <span data-ttu-id="8665d-188">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8665d-188">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-189">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-189">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, clustersListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clustersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-191">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-191">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clustersListByResourceGroupOptions">
            <span data-ttu-id="8665d-192">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8665d-192">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-194">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-194">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-197">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-197">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-199">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-201">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-201">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-204">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-204">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-208">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-208">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformation">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformation(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformation (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformation : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformation (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-210">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-210">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-211">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-211">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-212">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-212">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-213">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-213">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-214">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-214">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListRemoteLoginInformationAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-216">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-216">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-217">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-217">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-218">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-218">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-219">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-219">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-221">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-221">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNext(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformationNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNext : Microsoft.Azure.Management.BatchAI.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-223">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-224">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-224">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNextAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNextAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.ListRemoteLoginInformationNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;ListRemoteLoginInformationNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-225">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8665d-226">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8665d-226">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-228">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="8665d-228">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Cluster Update (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Cluster Update(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Update(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterUpdateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.Update (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-230">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-230">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-231">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-231">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-232">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-232">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-233">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-233">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-234">クラスター更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-234">Additional parameters for cluster update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-235">特定のクラスターのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8665d-235">Update the properties of a given cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; UpdateAsync (this Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt; UpdateAsync(class Microsoft.Azure.Management.BatchAI.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.BatchAI.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.BatchAI.IClustersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions.UpdateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.ClustersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8665d-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8665d-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8665d-237">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="8665d-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="8665d-238">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="8665d-238">The name of the cluster within the specified resource group.</span></span> <span data-ttu-id="8665d-239">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="8665d-239">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="8665d-240">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8665d-240">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8665d-241">クラスター更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8665d-241">Additional parameters for cluster update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8665d-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8665d-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8665d-243">特定のクラスターのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8665d-243">Update the properties of a given cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>