<Type Name="DataLakeStoreAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataLakeStoreAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d349f-101">DataLakeStoreAccountsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="d349f-101">Extension methods for DataLakeStoreAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String, Optional parameters As AddDataLakeStoreParameters = null)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-103">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-104">Data Lake Store アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-104">The name of the Data Lake Analytics account to which to add the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-105">追加する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-105">The name of the Data Lake Store account to add.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d349f-106">Data Lake Store アカウントの詳細。</span><span class="sxs-lookup"><span data-stu-id="d349f-106">The details of the Data Lake Store account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-107">含める追加の Data Lake Store アカウントに指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="d349f-107">Updates the specified Data Lake Analytics account to include the additional Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-109">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-109">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-110">Data Lake Store アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-110">The name of the Data Lake Analytics account to which to add the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-111">追加する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-111">The name of the Data Lake Store account to add.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d349f-112">Data Lake Store アカウントの詳細。</span><span class="sxs-lookup"><span data-stu-id="d349f-112">The details of the Data Lake Store account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d349f-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d349f-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-114">含める追加の Data Lake Store アカウントに指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="d349f-114">Updates the specified Data Lake Analytics account to include the additional Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-116">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-116">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-117">Data Lake Store アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-117">The name of the Data Lake Analytics account from which to remove the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-118">削除する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="d349f-118">The name of the Data Lake Store account to remove</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-119">指定された Data Lake Store アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="d349f-119">Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-121">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-121">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-122">Data Lake Store アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-122">The name of the Data Lake Analytics account from which to remove the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-123">削除する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="d349f-123">The name of the Data Lake Store account to remove</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d349f-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d349f-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-125">指定された Data Lake Store アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="d349f-125">Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String) As DataLakeStoreAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-127">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-127">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-128">Data Lake Store アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-128">The name of the Data Lake Analytics account from which to retrieve the Data Lake Store account details.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-129">取得する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="d349f-129">The name of the Data Lake Store account to retrieve</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-130">指定された Data Lake Analytics アカウントの指定された Data Lake Store アカウントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-130">Gets the specified Data Lake Store account details in the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-132">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-132">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-133">Data Lake Store アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-133">The name of the Data Lake Analytics account from which to retrieve the Data Lake Store account details.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="d349f-134">取得する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="d349f-134">The name of the Data Lake Store account to retrieve</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d349f-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d349f-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-136">指定された Data Lake Analytics アカウントの指定された Data Lake Store アカウントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-136">Gets the specified Data Lake Store account details in the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of DataLakeStoreAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-138">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-138">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-139">名前、Data Lake Analytics アカウントの Data Lake Store アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d349f-139">The name of the Data Lake Analytics account for which to list Data Lake Store accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="d349f-140">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d349f-140">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="d349f-141">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="d349f-141">OData Select statement.</span></span> <span data-ttu-id="d349f-142">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="d349f-142">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="d349f-143">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d349f-143">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="d349f-144">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="d349f-144">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="d349f-145">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d349f-145">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-146">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-146">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="d349f-147">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d349f-147">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d349f-149">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d349f-149">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d349f-150">名前、Data Lake Analytics アカウントの Data Lake Store アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d349f-150">The name of the Data Lake Analytics account for which to list Data Lake Store accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="d349f-151">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d349f-151">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="d349f-152">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="d349f-152">OData Select statement.</span></span> <span data-ttu-id="d349f-153">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="d349f-153">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="d349f-154">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d349f-154">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="d349f-155">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="d349f-155">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="d349f-156">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d349f-156">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d349f-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d349f-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-158">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-158">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="d349f-159">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d349f-159">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IDataLakeStoreAccountsOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-160">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d349f-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d349f-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-162">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-162">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="d349f-163">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d349f-163">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d349f-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d349f-164">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d349f-165">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d349f-165">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d349f-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d349f-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d349f-167">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="d349f-167">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="d349f-168">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d349f-168">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>