<Type Name="AccountOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccountOperationsExtensions = class" />
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
            <span data-ttu-id="1dcb5-101">AccountOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-101">Extension methods for AccountOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount BeginCreate (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount BeginCreate(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginCreate(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IAccountOperations, resourceGroupName As String, accountName As String, parameters As DataLakeAnalyticsAccount) As DataLakeAnalyticsAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-103">Data Lake Analytics account.the アカウントが含まれている Azure リソース グループの名前に関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-103">The name of the Azure resource group that contains the Data Lake Analytics account.the account will be associated with.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-104">作成する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-104">The name of the Data Lake Analytics account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-105">パラメーターは、作成する Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-105">Parameters supplied to the create Data Lake Analytics account operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-106">指定された Data Lake Analytics アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-106">Creates the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1dcb5-107">Data Lake Analytics ワークロード向けの計算サービスによりユーザーを提供します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-107">This supplies the user with computation services for Data Lake Analytics workloads</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;BeginCreateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-109">Data Lake Analytics account.the アカウントが含まれている Azure リソース グループの名前に関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-109">The name of the Azure resource group that contains the Data Lake Analytics account.the account will be associated with.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-110">作成する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-110">The name of the Data Lake Analytics account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-111">パラメーターは、作成する Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-111">Parameters supplied to the create Data Lake Analytics account operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-113">指定された Data Lake Analytics アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-113">Creates the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1dcb5-114">Data Lake Analytics ワークロード向けの計算サービスによりユーザーを提供します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-114">This supplies the user with computation services for Data Lake Analytics workloads</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-116">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-116">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-117">削除する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-117">The name of the Data Lake Analytics account to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-118">アカウント名で指定された Data Lake Analytics アカウント オブジェクトの削除プロセスを開始します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-118">Begins the delete process for the Data Lake Analytics account object specified by the account name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;BeginDeleteAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-120">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-120">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-121">削除する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-121">The name of the Data Lake Analytics account to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-123">アカウント名で指定された Data Lake Analytics アカウント オブジェクトの削除プロセスを開始します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-123">Begins the delete process for the Data Lake Analytics account object specified by the account name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount BeginUpdate (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount BeginUpdate(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IAccountOperations, resourceGroupName As String, accountName As String, Optional parameters As DataLakeAnalyticsAccountUpdateParameters = null) As DataLakeAnalyticsAccount" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginUpdate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-125">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-125">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-126">更新する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-126">The name of the Data Lake Analytics account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-127">パラメーターは、更新プログラムに Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-127">Parameters supplied to the update Data Lake Analytics account operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-128">Data Lake Analytics アカウントのアカウント オブジェクトの内容でアカウント名で指定されたオブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-128">Updates the Data Lake Analytics account object specified by the accountName with the contents of the account object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; BeginUpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; BeginUpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;BeginUpdateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-130">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-130">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-131">更新する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-131">The name of the Data Lake Analytics account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-132">パラメーターは、更新プログラムに Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-132">Parameters supplied to the update Data Lake Analytics account operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-134">Data Lake Analytics アカウントのアカウント オブジェクトの内容でアカウント名で指定されたオブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-134">Updates the Data Lake Analytics account object specified by the accountName with the contents of the account object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Create (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Create(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IAccountOperations, resourceGroupName As String, accountName As String, parameters As DataLakeAnalyticsAccount) As DataLakeAnalyticsAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-136">Data Lake Analytics account.the アカウントが含まれている Azure リソース グループの名前に関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-136">The name of the Azure resource group that contains the Data Lake Analytics account.the account will be associated with.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-137">作成する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-137">The name of the Data Lake Analytics account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-138">パラメーターは、作成する Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-138">Parameters supplied to the create Data Lake Analytics account operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-139">指定された Data Lake Analytics アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-139">Creates the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1dcb5-140">Data Lake Analytics ワークロード向けの計算サービスによりユーザーを提供します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-140">This supplies the user with computation services for Data Lake Analytics workloads</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; CreateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; CreateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-142">Data Lake Analytics account.the アカウントが含まれている Azure リソース グループの名前に関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-142">The name of the Azure resource group that contains the Data Lake Analytics account.the account will be associated with.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-143">作成する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-143">The name of the Data Lake Analytics account to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-144">パラメーターは、作成する Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-144">Parameters supplied to the create Data Lake Analytics account operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-146">指定された Data Lake Analytics アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-146">Creates the specified Data Lake Analytics account.</span></span> <span data-ttu-id="1dcb5-147">Data Lake Analytics ワークロード向けの計算サービスによりユーザーを提供します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-147">This supplies the user with computation services for Data Lake Analytics workloads</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccountExists">
      <MemberSignature Language="C#" Value="public static bool DataLakeStoreAccountExists (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool DataLakeStoreAccountExists(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DataLakeStoreAccountExists(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DataLakeStoreAccountExists (operations As IAccountOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member DataLakeStoreAccountExists : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DataLakeStoreAccountExists (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-149">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-149">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-150">Data Lake Store アカウントの存在をテストするための Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-150">The name of the Data Lake Analytics account from which to test the existence of the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="1dcb5-151">存在をテストする Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-151">The name of the Data Lake Store account to test for existence</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-152">指定された Data Lake Store アカウントが指定された Data Lake Analytics アカウントにリンクされているかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-152">Tests whether the specified Data Lake Store account is linked to the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccountExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; DataLakeStoreAccountExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; DataLakeStoreAccountExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DataLakeStoreAccountExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DataLakeStoreAccountExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DataLakeStoreAccountExistsAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;DataLakeStoreAccountExistsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-154">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-154">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-155">Data Lake Store アカウントの存在をテストするための Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-155">The name of the Data Lake Analytics account from which to test the existence of the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="1dcb5-156">存在をテストする Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-156">The name of the Data Lake Store account to test for existence</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-158">指定された Data Lake Store アカウントが指定された Data Lake Analytics アカウントにリンクされているかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-158">Tests whether the specified Data Lake Store account is linked to the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAccountOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-160">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-160">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-161">削除する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-161">The name of the Data Lake Analytics account to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-162">アカウント名で指定された Data Lake Analytics アカウント オブジェクトの削除プロセスを開始します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-162">Begins the delete process for the Data Lake Analytics account object specified by the account name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;DeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-164">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-164">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-165">削除する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="1dcb5-165">The name of the Data Lake Analytics account to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-167">アカウント名で指定された Data Lake Analytics アカウント オブジェクトの削除プロセスを開始します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-167">Begins the delete process for the Data Lake Analytics account object specified by the account name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Exists(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Exists (operations As IAccountOperations, resourceGroupName As String, accountName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Exists (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-169">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-169">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-170">存在をテストする Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-170">The name of the Data Lake Analytics account to test existence of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-171">指定された Data Lake Analytics アカウントの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-171">Tests for the existence of the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ExistsAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;ExistsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-173">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-173">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-174">存在をテストする Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-174">The name of the Data Lake Analytics account to test existence of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-176">指定された Data Lake Analytics アカウントの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-176">Tests for the existence of the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Get (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Get(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAccountOperations, resourceGroupName As String, accountName As String) As DataLakeAnalyticsAccount" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Get (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-178">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-178">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-179">取得する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-179">The name of the Data Lake Analytics account to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-180">指定された Data Lake Analytics アカウントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-180">Gets details of the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;GetAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-182">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-182">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-183">取得する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-183">The name of the Data Lake Analytics account to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-185">指定された Data Lake Analytics アカウントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-185">Gets details of the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAccountOperations, Optional odataQuery As ODataQuery(Of DataLakeAnalyticsAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeAnalyticsAccountBasic)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.List (operations, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-186">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1dcb5-187">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-187">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1dcb5-188">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-188">OData Select statement.</span></span> <span data-ttu-id="1dcb5-189">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-189">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1dcb5-190">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-190">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1dcb5-191">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-191">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1dcb5-192">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-192">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-193">現在のサブスクリプション内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-193">Gets the first page of Data Lake Analytics accounts, if any, within the current subscription.</span></span> <span data-ttu-id="1dcb5-194">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-194">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListAsync (operations, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-195">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1dcb5-196">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-196">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1dcb5-197">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-197">OData Select statement.</span></span> <span data-ttu-id="1dcb5-198">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-198">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1dcb5-199">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-199">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1dcb5-200">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-200">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1dcb5-201">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-201">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-203">現在のサブスクリプション内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-203">Gets the first page of Data Lake Analytics accounts, if any, within the current subscription.</span></span> <span data-ttu-id="1dcb5-204">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-204">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListByResourceGroup (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListByResourceGroup(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAccountOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of DataLakeAnalyticsAccount) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeAnalyticsAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-206">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-206">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1dcb5-207">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-207">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1dcb5-208">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-208">OData Select statement.</span></span> <span data-ttu-id="1dcb5-209">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-209">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1dcb5-210">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-210">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1dcb5-211">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-211">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1dcb5-212">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-212">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-213">特定のリソース グループ内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-213">Gets the first page of Data Lake Analytics accounts, if any, within a specific resource group.</span></span> <span data-ttu-id="1dcb5-214">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-214">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-216">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-216">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="1dcb5-217">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-217">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="1dcb5-218">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-218">OData Select statement.</span></span> <span data-ttu-id="1dcb5-219">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-219">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="1dcb5-220">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-220">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="1dcb5-221">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-221">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="1dcb5-222">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-222">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-223">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-224">特定のリソース グループ内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-224">Gets the first page of Data Lake Analytics accounts, if any, within a specific resource group.</span></span> <span data-ttu-id="1dcb5-225">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-225">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeAnalyticsAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-226">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1dcb5-227">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-227">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-228">特定のリソース グループ内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-228">Gets the first page of Data Lake Analytics accounts, if any, within a specific resource group.</span></span> <span data-ttu-id="1dcb5-229">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-229">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-230">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1dcb5-231">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-231">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-233">特定のリソース グループ内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-233">Gets the first page of Data Lake Analytics accounts, if any, within a specific resource group.</span></span> <span data-ttu-id="1dcb5-234">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-234">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAccountOperations, nextPageLink As String) As IPage(Of DataLakeAnalyticsAccountBasic)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-235">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1dcb5-236">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-236">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-237">現在のサブスクリプション内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-237">Gets the first page of Data Lake Analytics accounts, if any, within the current subscription.</span></span> <span data-ttu-id="1dcb5-238">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-238">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-239">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-239">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1dcb5-240">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-240">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-242">現在のサブスクリプション内に存在する場合は、Data Lake Analytics アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-242">Gets the first page of Data Lake Analytics accounts, if any, within the current subscription.</span></span> <span data-ttu-id="1dcb5-243">存在する場合、次のページへのリンクが含まれます。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-243">This includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountExists">
      <MemberSignature Language="C#" Value="public static bool StorageAccountExists (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool StorageAccountExists(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageAccountExists(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StorageAccountExists (operations As IAccountOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member StorageAccountExists : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageAccountExists (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-244">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-245">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-245">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-246">Azure ストレージ アカウントの存在をテストするための Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-246">The name of the Data Lake Analytics account from which to test Azure storage account existence.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1dcb5-247">存在をテストする対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-247">The name of the Azure Storage account for which to test for existence.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-248">指定された Azure ストレージ アカウントが、指定された Data Lake Analytics アカウントにリンクされているかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-248">Tests whether the specified Azure Storage account is linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; StorageAccountExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; StorageAccountExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageAccountExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StorageAccountExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageAccountExistsAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;StorageAccountExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-250">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-250">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-251">Azure ストレージ アカウントの存在をテストするための Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-251">The name of the Data Lake Analytics account from which to test Azure storage account existence.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1dcb5-252">存在をテストする対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-252">The name of the Azure Storage account for which to test for existence.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-254">指定された Azure ストレージ アカウントが、指定された Data Lake Analytics アカウントにリンクされているかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-254">Tests whether the specified Azure Storage account is linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageContainerExists">
      <MemberSignature Language="C#" Value="public static bool StorageContainerExists (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool StorageContainerExists(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageContainerExists(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StorageContainerExists (operations As IAccountOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member StorageContainerExists : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageContainerExists (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-256">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-256">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-257">Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-257">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1dcb5-258">Azure のストレージ アカウントから blob コンテナーの存在をテストするための名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-258">The name of the Azure storage account from which to test the blob container's existence.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1dcb5-259">存在をテストする Azure ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-259">The name of the Azure storage container to test for existence.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-260">特定の Data Lake Analytics と Azure ストレージ アカウントに関連付けられている、指定された Azure ストレージ コンテナーの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-260">Tests the existence of the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageContainerExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; StorageContainerExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; StorageContainerExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageContainerExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StorageContainerExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.StorageContainerExistsAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;StorageContainerExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-261">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-262">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-262">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-263">Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-263">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1dcb5-264">Azure のストレージ アカウントから blob コンテナーの存在をテストするための名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-264">The name of the Azure storage account from which to test the blob container's existence.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="1dcb5-265">存在をテストする Azure ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-265">The name of the Azure storage container to test for existence.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-267">特定の Data Lake Analytics と Azure ストレージ アカウントに関連付けられている、指定された Azure ストレージ コンテナーの存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-267">Tests the existence of the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Update (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount Update(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IAccountOperations, resourceGroupName As String, accountName As String, Optional parameters As DataLakeAnalyticsAccountUpdateParameters = null) As DataLakeAnalyticsAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-268">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-268">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-269">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-269">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-270">更新する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-270">The name of the Data Lake Analytics account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-271">パラメーターは、更新プログラムに Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-271">Parameters supplied to the update Data Lake Analytics account operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-272">Data Lake Analytics アカウントのアカウント オブジェクトの内容でアカウント名で指定されたオブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-272">Updates the Data Lake Analytics account object specified by the accountName with the contents of the account object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.AccountOperationsExtensions/&lt;UpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dcb5-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dcb5-274">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-274">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1dcb5-275">更新する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-275">The name of the Data Lake Analytics account to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1dcb5-276">パラメーターは、更新プログラムに Data Lake Analytics アカウントの操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-276">Parameters supplied to the update Data Lake Analytics account operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dcb5-277">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dcb5-278">Data Lake Analytics アカウントのアカウント オブジェクトの内容でアカウント名で指定されたオブジェクトを更新します。</span><span class="sxs-lookup"><span data-stu-id="1dcb5-278">Updates the Data Lake Analytics account object specified by the accountName with the contents of the account object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>