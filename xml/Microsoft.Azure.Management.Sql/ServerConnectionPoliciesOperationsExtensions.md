<Type Name="ServerConnectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerConnectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerConnectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerConnectionPoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="a2138-101">ServerConnectionPoliciesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a2138-101">Extension methods for ServerConnectionPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerConnectionPoliciesOperations, resourceGroupName As String, serverName As String, parameters As ServerConnectionPolicy) As ServerConnectionPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2138-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2138-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2138-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2138-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2138-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2138-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-105">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a2138-106">セキュリティで保護された接続ポリシーを更新するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a2138-106">The required parameters for updating a secure connection policy.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2138-107">作成するか、サーバーの接続のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a2138-107">Creates or updates the server's connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2138-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2138-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2138-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2138-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2138-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2138-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-111">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a2138-112">セキュリティで保護された接続ポリシーを更新するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="a2138-112">The required parameters for updating a secure connection policy.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2138-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2138-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2138-114">作成するか、サーバーの接続のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="a2138-114">Creates or updates the server's connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy Get (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy Get(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerConnectionPoliciesOperations, resourceGroupName As String, serverName As String) As ServerConnectionPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2138-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2138-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2138-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2138-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2138-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2138-118">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-118">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2138-119">サーバーのセキュリティで保護された接続ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a2138-119">Gets the server's secure connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerConnectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2138-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a2138-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a2138-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="a2138-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="a2138-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="a2138-123">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="a2138-123">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2138-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2138-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2138-125">サーバーのセキュリティで保護された接続ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="a2138-125">Gets the server's secure connection policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>