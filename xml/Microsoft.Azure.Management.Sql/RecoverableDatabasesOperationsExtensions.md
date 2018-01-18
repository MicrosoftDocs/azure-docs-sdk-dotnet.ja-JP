<Type Name="RecoverableDatabasesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecoverableDatabasesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecoverableDatabasesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecoverableDatabasesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecoverableDatabasesOperationsExtensions = class" />
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
            <span data-ttu-id="a68f1-101">RecoverableDatabasesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a68f1-101">Extension methods for RecoverableDatabasesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.RecoverableDatabase Get (this Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase Get(class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecoverableDatabasesOperations, resourceGroupName As String, serverName As String, databaseName As String) As RecoverableDatabase" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.RecoverableDatabase" Usage="Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.RecoverableDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a68f1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a68f1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a68f1-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a68f1-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a68f1-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a68f1-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a68f1-106">データベースの名前</span><span class="sxs-lookup"><span data-stu-id="a68f1-106">The name of the database</span></span>
            </param>
        <summary>
            <span data-ttu-id="a68f1-107">表すデータベースの地理的バックアップをリソースでは、回復可能なデータベースを取得</span><span class="sxs-lookup"><span data-stu-id="a68f1-107">Gets a recoverable database, which is a resource representing a database's geo backup</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt; GetAsync (this Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt; GetAsync(class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a68f1-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a68f1-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a68f1-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a68f1-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a68f1-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a68f1-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-111">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="a68f1-112">データベースの名前</span><span class="sxs-lookup"><span data-stu-id="a68f1-112">The name of the database</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a68f1-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a68f1-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a68f1-114">表すデータベースの地理的バックアップをリソースでは、回復可能なデータベースを取得</span><span class="sxs-lookup"><span data-stu-id="a68f1-114">Gets a recoverable database, which is a resource representing a database's geo backup</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt; ListByServer (this Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt; ListByServer(class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IRecoverableDatabasesOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of RecoverableDatabase)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;" Usage="Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a68f1-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a68f1-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a68f1-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a68f1-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a68f1-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a68f1-118">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-118">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a68f1-119">回復可能なデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a68f1-119">Gets a list of recoverable databases</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecoverableDatabasesOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecoverableDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a68f1-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a68f1-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a68f1-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a68f1-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a68f1-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a68f1-123">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a68f1-123">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a68f1-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a68f1-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a68f1-125">回復可能なデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a68f1-125">Gets a list of recoverable databases</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>