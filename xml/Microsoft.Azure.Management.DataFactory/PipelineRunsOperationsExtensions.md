<Type Name="PipelineRunsOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelineRunsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelineRunsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelineRunsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelineRunsOperationsExtensions = class" />
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
            <span data-ttu-id="f66f5-101">PipelineRunsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f66f5-101">Extension methods for PipelineRunsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineRun Get (this Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineRun Get(class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.Get(Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelineRunsOperations, resourceGroupName As String, factoryName As String, runId As String) As PipelineRun" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRun" Usage="Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.Get (operations, resourceGroupName, factoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f66f5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f66f5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f66f5-103">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f66f5-103">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f66f5-104">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f66f5-104">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="f66f5-105">実行の識別子のパイプライン。</span><span class="sxs-lookup"><span data-stu-id="f66f5-105">The pipeline run identifier.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f66f5-106">実行 ID によって実行パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="f66f5-106">Get a pipeline run by its run ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; GetAsync (this Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, string runId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt; GetAsync(class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.GetAsync (operations, resourceGroupName, factoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f66f5-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f66f5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f66f5-108">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f66f5-108">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f66f5-109">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f66f5-109">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="f66f5-110">実行の識別子のパイプライン。</span><span class="sxs-lookup"><span data-stu-id="f66f5-110">The pipeline run identifier.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f66f5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f66f5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f66f5-112">実行 ID によって実行パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="f66f5-112">Get a pipeline run by its run ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryByFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse QueryByFactory (this Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse QueryByFactory(class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.QueryByFactory(Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function QueryByFactory (operations As IPipelineRunsOperations, resourceGroupName As String, factoryName As String, filterParameters As PipelineRunFilterParameters) As PipelineRunQueryResponse" />
      <MemberSignature Language="F#" Value="static member QueryByFactory : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse" Usage="Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.QueryByFactory (operations, resourceGroupName, factoryName, filterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="filterParameters" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f66f5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f66f5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f66f5-114">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f66f5-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f66f5-115">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f66f5-115">The factory name.</span></span>
            </param>
        <param name="filterParameters">
            <span data-ttu-id="f66f5-116">パラメーターをパイプラインをフィルター処理を実行します。</span><span class="sxs-lookup"><span data-stu-id="f66f5-116">Parameters to filter the pipeline run.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f66f5-117">クエリ パイプラインは、入力のフィルター条件に基づいてファクトリで実行されます。</span><span class="sxs-lookup"><span data-stu-id="f66f5-117">Query pipeline runs in the factory based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryByFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt; QueryByFactoryAsync (this Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt; QueryByFactoryAsync(class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations operations, string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.QueryByFactoryAsync(Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member QueryByFactoryAsync : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;" Usage="Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions.QueryByFactoryAsync (operations, resourceGroupName, factoryName, filterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactory.PipelineRunsOperationsExtensions/&lt;QueryByFactoryAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="filterParameters" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f66f5-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f66f5-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f66f5-119">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f66f5-119">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f66f5-120">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f66f5-120">The factory name.</span></span>
            </param>
        <param name="filterParameters">
            <span data-ttu-id="f66f5-121">パラメーターをパイプラインをフィルター処理を実行します。</span><span class="sxs-lookup"><span data-stu-id="f66f5-121">Parameters to filter the pipeline run.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f66f5-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f66f5-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f66f5-123">クエリ パイプラインは、入力のフィルター条件に基づいてファクトリで実行されます。</span><span class="sxs-lookup"><span data-stu-id="f66f5-123">Query pipeline runs in the factory based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>