<Type Name="DatasetsOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatasetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatasetsOperationsExtensions = class" />
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
            <span data-ttu-id="8117f-101">DatasetsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8117f-101">Extension methods for DatasetsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.DatasetResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, Microsoft.Azure.Management.DataFactory.Models.DatasetResource dataset, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.DatasetResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, class Microsoft.Azure.Management.DataFactory.Models.DatasetResource dataset, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.DatasetResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatasetsOperations, resourceGroupName As String, factoryName As String, datasetName As String, dataset As DatasetResource, Optional ifMatch As String = null) As DatasetResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.DatasetResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.DatasetResource" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, datasetName, dataset, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-104">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-105">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-105">The dataset name.</span></span>
            </param>
        <param name="dataset">
            <span data-ttu-id="8117f-106">リソース定義のデータセット。</span><span class="sxs-lookup"><span data-stu-id="8117f-106">Dataset resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8117f-107">データセットのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="8117f-107">ETag of the dataset entity.</span></span>  <span data-ttu-id="8117f-108">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="8117f-108">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-109">作成するか、データセットを更新します。</span><span class="sxs-lookup"><span data-stu-id="8117f-109">Creates or updates a dataset.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, Microsoft.Azure.Management.DataFactory.Models.DatasetResource dataset, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, class Microsoft.Azure.Management.DataFactory.Models.DatasetResource dataset, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.DatasetResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.DatasetResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, datasetName, dataset, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-111">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-112">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-112">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-113">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-113">The dataset name.</span></span>
            </param>
        <param name="dataset">
            <span data-ttu-id="8117f-114">リソース定義のデータセット。</span><span class="sxs-lookup"><span data-stu-id="8117f-114">Dataset resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8117f-115">データセットのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="8117f-115">ETag of the dataset entity.</span></span>  <span data-ttu-id="8117f-116">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="8117f-116">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8117f-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8117f-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-118">作成するか、データセットを更新します。</span><span class="sxs-lookup"><span data-stu-id="8117f-118">Creates or updates a dataset.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDatasetsOperations, resourceGroupName As String, factoryName As String, datasetName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.Delete (operations, resourceGroupName, factoryName, datasetName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-120">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-120">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-121">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-121">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-122">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-122">The dataset name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-123">データセットを削除します。</span><span class="sxs-lookup"><span data-stu-id="8117f-123">Deletes a dataset.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, datasetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-125">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-125">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-126">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-126">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-127">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-127">The dataset name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8117f-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8117f-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-129">データセットを削除します。</span><span class="sxs-lookup"><span data-stu-id="8117f-129">Deletes a dataset.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.DatasetResource Get (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.DatasetResource Get(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatasetsOperations, resourceGroupName As String, factoryName As String, datasetName As String) As DatasetResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.DatasetResource" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.Get (operations, resourceGroupName, factoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-131">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-131">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-132">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-132">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-133">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-133">The dataset name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-134">データセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="8117f-134">Gets a dataset.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, datasetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-136">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-136">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-137">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-137">The factory name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="8117f-138">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="8117f-138">The dataset name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8117f-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8117f-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-140">データセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="8117f-140">Gets a dataset.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IDatasetsOperations, resourceGroupName As String, factoryName As String) As IPage(Of DatasetResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-142">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-142">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-143">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-143">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-144">データセットの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="8117f-144">Lists datasets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8117f-146">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="8117f-146">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="8117f-147">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="8117f-147">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8117f-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8117f-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-149">データセットの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="8117f-149">Lists datasets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IDatasetsOperations, nextPageLink As String) As IPage(Of DatasetResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8117f-151">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8117f-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-152">データセットの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="8117f-152">Lists datasets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IDatasetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IDatasetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IDatasetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.DatasetsOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.DatasetResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IDatasetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8117f-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8117f-153">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8117f-154">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8117f-154">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8117f-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8117f-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8117f-156">データセットの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="8117f-156">Lists datasets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>