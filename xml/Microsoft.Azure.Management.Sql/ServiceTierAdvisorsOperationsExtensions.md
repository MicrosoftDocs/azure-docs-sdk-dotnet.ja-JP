<Type Name="ServiceTierAdvisorsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceTierAdvisorsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServiceTierAdvisorsOperationsExtensions = class" />
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
            <span data-ttu-id="10208-101">ServiceTierAdvisorsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="10208-101">Extension methods for ServiceTierAdvisorsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor Get (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor Get(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServiceTierAdvisorsOperations, resourceGroupName As String, serverName As String, databaseName As String, serviceTierAdvisorName As String) As ServiceTierAdvisor" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10208-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10208-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10208-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="10208-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="10208-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="10208-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="10208-106">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-106">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="10208-107">サービス層アドバイザーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-107">The name of service tier advisor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10208-108">サービス層アドバイザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="10208-108">Gets a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10208-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10208-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10208-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="10208-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="10208-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="10208-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="10208-113">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-113">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="10208-114">サービス層アドバイザーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-114">The name of service tier advisor.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10208-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10208-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10208-116">サービス層アドバイザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="10208-116">Gets a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IServiceTierAdvisorsOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10208-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10208-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10208-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="10208-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="10208-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="10208-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="10208-121">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-121">The name of database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10208-122">サービス層アドバイザー指定されたデータベースを返します。</span><span class="sxs-lookup"><span data-stu-id="10208-122">Returns service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10208-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10208-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="10208-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="10208-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="10208-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="10208-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="10208-127">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="10208-127">The name of database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10208-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10208-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10208-129">サービス層アドバイザー指定されたデータベースを返します。</span><span class="sxs-lookup"><span data-stu-id="10208-129">Returns service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>