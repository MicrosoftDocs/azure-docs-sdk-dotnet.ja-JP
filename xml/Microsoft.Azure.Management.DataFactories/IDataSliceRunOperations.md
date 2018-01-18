<Type Name="IDataSliceRunOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceRunOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceRunOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceRunOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceRunOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="93efd-101">データ スライスの実行を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="93efd-101">Operations for managing data slice runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string runId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="iDataSliceRunOperations.GetAsync (resourceGroupName, dataFactoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="93efd-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="93efd-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="93efd-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="93efd-103">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="93efd-104">一意のデータ スライスの実行の id。</span><span class="sxs-lookup"><span data-stu-id="93efd-104">A unique Data Slice Run Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="93efd-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="93efd-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="93efd-106">データ スライスの実行のインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="93efd-106">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="93efd-107">Get 操作の応答のデータ スライスを実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-107">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (string resourceGroupName, string dataFactoryName, string dataSliceRunId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(string resourceGroupName, string dataFactoryName, string dataSliceRunId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.GetLogsAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLogsAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="iDataSliceRunOperations.GetLogsAsync (resourceGroupName, dataFactoryName, dataSliceRunId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="93efd-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="93efd-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="93efd-109">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="93efd-109">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="93efd-110">一意のデータ スライスは、インスタンス id を実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-110">A unique data slice run instance id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="93efd-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="93efd-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="93efd-112">データ スライスの実行のログを取得します。</span><span class="sxs-lookup"><span data-stu-id="93efd-112">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="93efd-113">データ スライスは、get ログ操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-113">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="93efd-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="93efd-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="93efd-115">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="93efd-115">A unique data factory instance name.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="93efd-116">一意テーブルのインスタンス名。</span><span class="sxs-lookup"><span data-stu-id="93efd-116">A unique table instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="93efd-117">テーブルのデータ スライスの一覧にフィルターを指定するためのパラメーターが実行されます。</span><span class="sxs-lookup"><span data-stu-id="93efd-117">Parameters for specifying the filters to list data slice runs of the table.</span></span>
            <span data-ttu-id="93efd-118">(</span><span class="sxs-lookup"><span data-stu-id="93efd-118">format.</span></span>
            </param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="93efd-119">次のページにリンクを使用してインスタンスを実行するデータ スライスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="93efd-119">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="93efd-120">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-120">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="93efd-121">次のデータ スライスへの url は、ページを実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-121">The url to the next data slice runs page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="93efd-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="93efd-122">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="93efd-123">次のページへのリンクを持つ実行のインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="93efd-123">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="93efd-124">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="93efd-124">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>