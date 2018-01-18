<Type Name="IDataSliceOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1d2c-101">データ スライスを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-101">Operations for managing data slices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b1d2c-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b1d2c-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-103">A unique data factory instance name.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="b1d2c-104">一意テーブルのインスタンス名。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-104">A unique table instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b1d2c-105">テーブルのデータ スライスを一覧表示する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-105">Parameters specifying how to list data slices of the table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b1d2c-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1d2c-107">次のページにリンクを使用してデータ スライスのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-107">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1d2c-108">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-108">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="b1d2c-109">次のデータ スライスのページの url です。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-109">The url to the next data slices page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b1d2c-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1d2c-111">次のページにリンクを使用してデータ スライスのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-111">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1d2c-112">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-112">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.SetStatusAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStatusAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataSliceOperations.SetStatusAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b1d2c-113">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-113">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b1d2c-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-114">A unique data factory instance name.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="b1d2c-115">一意テーブルのインスタンス名。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-115">A unique table instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b1d2c-116">データ スライスの状態を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-116">The parameters required to set status of data slices.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b1d2c-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1d2c-118">特定のテーブルに対しての時間範囲には、データ スライスの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="b1d2c-118">Sets status of data slices over a time range for a specific table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b1d2c-119">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="b1d2c-119">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>