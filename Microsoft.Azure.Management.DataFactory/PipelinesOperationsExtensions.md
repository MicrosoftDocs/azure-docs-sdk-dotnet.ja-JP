<Type Name="PipelinesOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelinesOperationsExtensions = class" />
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
            <span data-ttu-id="458f0-101">PipelinesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="458f0-101">Extension methods for PipelinesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource CreateOrUpdate(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, pipeline As PipelineResource, Optional ifMatch As String = null) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-104">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-105">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-105">The pipeline name.</span></span>
            </param>
        <param name="pipeline">
            <span data-ttu-id="458f0-106">リソース定義をパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="458f0-106">Pipeline resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="458f0-107">パイプラインのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="458f0-107">ETag of the pipeline entity.</span></span>  <span data-ttu-id="458f0-108">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="458f0-108">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-109">作成するか、パイプラインを更新します。</span><span class="sxs-lookup"><span data-stu-id="458f0-109">Creates or updates a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, factoryName, pipelineName, pipeline, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-111">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-112">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-112">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-113">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-113">The pipeline name.</span></span>
            </param>
        <param name="pipeline">
            <span data-ttu-id="458f0-114">リソース定義をパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="458f0-114">Pipeline resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="458f0-115">パイプラインのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="458f0-115">ETag of the pipeline entity.</span></span>  <span data-ttu-id="458f0-116">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="458f0-116">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-118">作成するか、パイプラインを更新します。</span><span class="sxs-lookup"><span data-stu-id="458f0-118">Creates or updates a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRun">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse CreateRun(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateRun (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String, Optional parameters As IDictionary(Of String, Object) = null) As CreateRunResponse" />
      <MemberSignature Language="F#" Value="static member CreateRun : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRun (operations, resourceGroupName, factoryName, pipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-120">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-120">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-121">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-121">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-122">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-122">The pipeline name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="458f0-123">パイプラインのパラメーターを実行します。</span><span class="sxs-lookup"><span data-stu-id="458f0-123">Parameters of the pipeline run.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-124">パイプラインの実行を作成します。</span><span class="sxs-lookup"><span data-stu-id="458f0-124">Creates a run of a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt; CreateRunAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateRunAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.CreateRunAsync (operations, resourceGroupName, factoryName, pipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;CreateRunAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-126">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-126">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-127">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-127">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-128">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-128">The pipeline name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="458f0-129">パイプラインのパラメーターを実行します。</span><span class="sxs-lookup"><span data-stu-id="458f0-129">Parameters of the pipeline run.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-131">パイプラインの実行を作成します。</span><span class="sxs-lookup"><span data-stu-id="458f0-131">Creates a run of a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Delete (operations, resourceGroupName, factoryName, pipelineName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-133">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-133">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-134">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-134">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-135">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-135">The pipeline name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-136">パイプラインを削除します。</span><span class="sxs-lookup"><span data-stu-id="458f0-136">Deletes a pipeline.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-138">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-138">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-139">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-139">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-140">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-140">The pipeline name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-142">パイプラインを削除します。</span><span class="sxs-lookup"><span data-stu-id="458f0-142">Deletes a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineResource Get(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String, pipelineName As String) As PipelineResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.Get (operations, resourceGroupName, factoryName, pipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-144">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-144">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-145">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-145">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-146">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-146">The pipeline name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-147">パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="458f0-147">Gets a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, string pipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, pipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-149">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-149">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-150">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-150">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="458f0-151">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-151">The pipeline name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-153">パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="458f0-153">Gets a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactory(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactory (operations As IPipelinesOperations, resourceGroupName As String, factoryName As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactory : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactory (operations, resourceGroupName, factoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-155">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-155">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-156">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-156">The factory name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-157">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="458f0-157">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string resourceGroupName, string factoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryAsync (operations, resourceGroupName, factoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="458f0-159">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="458f0-159">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="458f0-160">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="458f0-160">The factory name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-162">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="458f0-162">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt; ListByFactoryNext(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByFactoryNext (operations As IPipelinesOperations, nextPageLink As String) As IPage(Of PipelineResource)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNext : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="458f0-164">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="458f0-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-165">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="458f0-165">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync (this Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; ListByFactoryNextAsync(class Microsoft.Azure.Management.DataFactory.IPipelinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync(Microsoft.Azure.Management.DataFactory.IPipelinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByFactoryNextAsync : Microsoft.Azure.Management.DataFactory.IPipelinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions.ListByFactoryNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelinesOperationsExtensions/&lt;ListByFactoryNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="458f0-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="458f0-166">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="458f0-167">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="458f0-167">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="458f0-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="458f0-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="458f0-169">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="458f0-169">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>