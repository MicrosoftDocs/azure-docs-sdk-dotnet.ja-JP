<Type Name="DataSourcesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourcesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="01925-101">DataSourcesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="01925-101">Extension methods for DataSourcesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String, parameters As DataSource) As DataSource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, dataSourceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-103">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-103">The name of the resource group to get.</span></span> <span data-ttu-id="01925-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-105">データ ソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="01925-105">Name of the Log Analytics Workspace that will contain the datasource</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-106">データ ソースのリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-106">The name of the datasource resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01925-107">作成またはデータ ソースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01925-107">The parameters required to create or update a datasource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-108">作成またはデータ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="01925-108">Create or update a data source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, dataSourceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-110">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-110">The name of the resource group to get.</span></span> <span data-ttu-id="01925-111">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-112">データ ソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="01925-112">Name of the Log Analytics Workspace that will contain the datasource</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-113">データ ソースのリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-113">The name of the datasource resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01925-114">作成またはデータ ソースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01925-114">The parameters required to create or update a datasource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01925-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01925-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-116">作成またはデータ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="01925-116">Create or update a data source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-118">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-118">The name of the resource group to get.</span></span> <span data-ttu-id="01925-119">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-120">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-120">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-121">データ ソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-121">Name of the datasource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-122">データ ソースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01925-122">Deletes a data source instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-124">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-124">The name of the resource group to get.</span></span> <span data-ttu-id="01925-125">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-126">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-126">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-127">データ ソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-127">Name of the datasource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01925-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01925-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-129">データ ソースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01925-129">Deletes a data source instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.DataSource Get(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataSourcesOperations, resourceGroupName As String, workspaceName As String, dataSourceName As String) As DataSource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSource" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, dataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-131">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-131">The name of the resource group to get.</span></span> <span data-ttu-id="01925-132">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-133">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-133">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-134">データソースの名前</span><span class="sxs-lookup"><span data-stu-id="01925-134">Name of the datasource</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-135">データ ソース インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-135">Gets a datasource instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string resourceGroupName, string workspaceName, string dataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, dataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-137">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-137">The name of the resource group to get.</span></span> <span data-ttu-id="01925-138">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-139">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="01925-139">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="01925-140">データソースの名前</span><span class="sxs-lookup"><span data-stu-id="01925-140">Name of the datasource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01925-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01925-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-142">データ ソース インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-142">Gets a datasource instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As IDataSourcesOperations, odataQuery As ODataQuery(Of DataSourceFilter), resourceGroupName As String, workspaceName As String, Optional skiptoken As String = null) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspace (operations, odataQuery, resourceGroupName, workspaceName, skiptoken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-143">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="01925-144">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="01925-144">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-145">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-145">The name of the resource group to get.</span></span> <span data-ttu-id="01925-146">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-146">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-147">データ ソースを含むワークスペースです。</span><span class="sxs-lookup"><span data-stu-id="01925-147">The workspace that contains the data sources.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="01925-148">データ ソース インスタンスのコレクションの開始点です。</span><span class="sxs-lookup"><span data-stu-id="01925-148">Starting point of the collection of data source instances.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-149">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-149">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceAsync (operations, odataQuery, resourceGroupName, workspaceName, skiptoken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-150">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="01925-151">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="01925-151">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01925-152">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01925-152">The name of the resource group to get.</span></span> <span data-ttu-id="01925-153">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="01925-153">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="01925-154">データ ソースを含むワークスペースです。</span><span class="sxs-lookup"><span data-stu-id="01925-154">The workspace that contains the data sources.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="01925-155">データ ソース インスタンスのコレクションの開始点です。</span><span class="sxs-lookup"><span data-stu-id="01925-155">Starting point of the collection of data source instances.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01925-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01925-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-157">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-157">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt; ListByWorkspaceNext(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspaceNext (operations As IDataSourcesOperations, nextPageLink As String) As IPage(Of DataSource)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNext : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01925-159">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01925-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-160">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-160">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync (this Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; ListByWorkspaceNextAsync(class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync(Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNextAsync : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions.ListByWorkspaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.DataSourcesOperationsExtensions/&lt;ListByWorkspaceNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01925-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01925-161">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01925-162">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01925-162">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01925-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01925-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01925-164">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="01925-164">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>