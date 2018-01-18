<Type Name="ComputePoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputePoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputePoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputePoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="a1dbc-101">ComputePoliciesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-101">Extension methods for ComputePoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy CreateOrUpdate(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, parameters As ComputePolicyCreateOrUpdateParameters) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-103">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-104">Data Lake Analytics アカウントを追加または置き換えるコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-104">The name of the Data Lake Analytics account to add or replace the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-105">作成または更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-105">The name of the compute policy to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1dbc-106">作成またはコンピューティング ポリシーの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-106">Parameters supplied to create or update the compute policy.</span></span> <span data-ttu-id="a1dbc-107">ジョブのプロパティごとの並列処理の次数の最大値、ジョブのプロパティ、またはその両方あたり最小優先度は存在しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-107">The max degree of parallelism per job property, min priority per job property, or both must be present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-108">作成するか、指定された計算ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-108">Creates or updates the specified compute policy.</span></span> <span data-ttu-id="a1dbc-109">更新中に、指定した名前を持つコンピューティング ポリシーはこの新しいコンピューティング ポリシーに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-109">During update, the compute policy with the specified name will be replaced with this new compute policy.</span></span> <span data-ttu-id="a1dbc-110">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-110">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-112">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-112">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-113">Data Lake Analytics アカウントを追加または置き換えるコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-113">The name of the Data Lake Analytics account to add or replace the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-114">作成または更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-114">The name of the compute policy to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1dbc-115">作成またはコンピューティング ポリシーの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-115">Parameters supplied to create or update the compute policy.</span></span> <span data-ttu-id="a1dbc-116">ジョブのプロパティごとの並列処理の次数の最大値、ジョブのプロパティ、またはその両方あたり最小優先度は存在しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-116">The max degree of parallelism per job property, min priority per job property, or both must be present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-118">作成するか、指定された計算ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-118">Creates or updates the specified compute policy.</span></span> <span data-ttu-id="a1dbc-119">更新中に、指定した名前を持つコンピューティング ポリシーはこの新しいコンピューティング ポリシーに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-119">During update, the compute policy with the specified name will be replaced with this new compute policy.</span></span> <span data-ttu-id="a1dbc-120">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-120">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Delete (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-122">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-122">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-123">コンピューティングのポリシーを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-123">The name of the Data Lake Analytics account from which to delete the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-124">削除するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-124">The name of the compute policy to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-125">指定された Data Lake Analytics アカウントから指定された計算のポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-125">Deletes the specified compute policy from the specified Data Lake Analytics account</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-127">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-127">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-128">コンピューティングのポリシーを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-128">The name of the Data Lake Analytics account from which to delete the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-129">削除するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-129">The name of the compute policy to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-131">指定された Data Lake Analytics アカウントから指定された計算のポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-131">Deletes the specified compute policy from the specified Data Lake Analytics account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Get(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Get (operations, resourceGroupName, accountName, computePolicyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-133">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-133">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-134">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-134">The name of the Data Lake Analytics account from which to get the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-135">取得するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-135">The name of the compute policy to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-136">指定された Data Lake Analytics 計算のポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-136">Gets the specified Data Lake Analytics compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, computePolicyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-138">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-138">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-139">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-139">The name of the Data Lake Analytics account from which to get the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-140">取得するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-140">The name of the compute policy to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-142">指定された Data Lake Analytics 計算のポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-142">Gets the specified Data Lake Analytics compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-144">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-144">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-145">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-145">The name of the Data Lake Analytics account from which to get the compute policies.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-146">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-146">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="a1dbc-147">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-147">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-149">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-149">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-150">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-150">The name of the Data Lake Analytics account from which to get the compute policies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-152">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-152">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="a1dbc-153">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-153">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IComputePoliciesOperations, nextPageLink As String) As IPage(Of ComputePolicy)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1dbc-155">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-156">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-156">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="a1dbc-157">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-157">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a1dbc-159">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-161">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-161">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="a1dbc-162">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="a1dbc-162">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy Update(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IComputePoliciesOperations, resourceGroupName As String, accountName As String, computePolicyName As String, Optional parameters As ComputePolicy = null) As ComputePolicy" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.Update (operations, resourceGroupName, accountName, computePolicyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-164">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-164">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-165">コンピューティング ポリシーを更新するために、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-165">The name of the Data Lake Analytics account to which to update the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-166">更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-166">The name of the compute policy to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1dbc-167">コンピューティングのポリシーの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-167">Parameters supplied to update the compute policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-168">指定された計算のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-168">Updates the specified compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt; UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations operations, string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, computePolicyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.ComputePoliciesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a1dbc-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a1dbc-170">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-170">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="a1dbc-171">コンピューティング ポリシーを更新するために、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-171">The name of the Data Lake Analytics account to which to update the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="a1dbc-172">更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-172">The name of the compute policy to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a1dbc-173">コンピューティングのポリシーの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-173">Parameters supplied to update the compute policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a1dbc-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a1dbc-175">指定された計算のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a1dbc-175">Updates the specified compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>