<Type Name="DataMaskingPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataMaskingPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataMaskingPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23dde-101">DataMaskingPoliciesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="23dde-101">Extension methods for DataMaskingPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataMaskingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DataMaskingPolicy) As DataMaskingPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23dde-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="23dde-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23dde-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="23dde-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="23dde-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="23dde-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="23dde-106">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-106">The name of the database.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="23dde-107">作成またはデータ マスキング ポリシーを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="23dde-107">Parameters for creating or updating a data masking policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23dde-108">作成するか、データベースのデータ マスキング ポリシーの更新</span><span class="sxs-lookup"><span data-stu-id="23dde-108">Creates or updates a database data masking policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23dde-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="23dde-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23dde-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="23dde-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="23dde-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="23dde-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="23dde-113">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-113">The name of the database.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="23dde-114">作成またはデータ マスキング ポリシーを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="23dde-114">Parameters for creating or updating a data masking policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23dde-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23dde-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23dde-116">作成するか、データベースのデータ マスキング ポリシーの更新</span><span class="sxs-lookup"><span data-stu-id="23dde-116">Creates or updates a database data masking policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy Get (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy Get(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataMaskingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As DataMaskingPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23dde-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="23dde-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23dde-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="23dde-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="23dde-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="23dde-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="23dde-121">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-121">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23dde-122">データベース データ マスキング ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="23dde-122">Gets a database data masking policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23dde-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="23dde-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23dde-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="23dde-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="23dde-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="23dde-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="23dde-127">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="23dde-127">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23dde-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="23dde-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23dde-129">データベース データ マスキング ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="23dde-129">Gets a database data masking policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>