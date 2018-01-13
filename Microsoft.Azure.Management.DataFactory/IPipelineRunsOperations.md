<Type Name="IPipelineRunsOperations" FullName="Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations">
  <TypeSignature Language="C#" Value="public interface IPipelineRunsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelineRunsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelineRunsOperations" />
  <TypeSignature Language="F#" Value="type IPipelineRunsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1abb0-101">PipelineRunsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="1abb0-101">PipelineRunsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string runId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string runId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt;" Usage="iPipelineRunsOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, runId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRun&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1abb0-102">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1abb0-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1abb0-103">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="1abb0-103">The factory name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="1abb0-104">実行の識別子のパイプライン。</span><span class="sxs-lookup"><span data-stu-id="1abb0-104">The pipeline run identifier.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1abb0-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1abb0-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1abb0-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1abb0-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1abb0-107">実行 ID によって実行パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="1abb0-107">Get a pipeline run by its run ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="1abb0-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1abb0-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1abb0-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="QueryByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt; QueryByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt; QueryByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters filterParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations.QueryByFactoryWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member QueryByFactoryWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt;" Usage="iPipelineRunsOperations.QueryByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, filterParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="filterParameters" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineRunFilterParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1abb0-111">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1abb0-111">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="1abb0-112">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="1abb0-112">The factory name.</span></span>
            </param>
        <param name="filterParameters">
            <span data-ttu-id="1abb0-113">パラメーターをパイプラインをフィルター処理を実行します。</span><span class="sxs-lookup"><span data-stu-id="1abb0-113">Parameters to filter the pipeline run.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1abb0-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1abb0-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1abb0-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1abb0-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1abb0-116">クエリ パイプラインは、入力のフィルター条件に基づいてファクトリで実行されます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-116">Query pipeline runs in the factory based on input filter conditions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="1abb0-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1abb0-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1abb0-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1abb0-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>