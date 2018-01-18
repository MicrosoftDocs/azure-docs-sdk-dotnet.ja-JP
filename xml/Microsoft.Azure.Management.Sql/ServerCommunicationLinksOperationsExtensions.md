<Type Name="ServerCommunicationLinksOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerCommunicationLinksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerCommunicationLinksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerCommunicationLinksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerCommunicationLinksOperationsExtensions = class" />
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
            <span data-ttu-id="de6ad-101">ServerCommunicationLinksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="de6ad-101">Extension methods for ServerCommunicationLinksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServerCommunicationLinksOperations, resourceGroupName As String, serverName As String, communicationLinkName As String, parameters As ServerCommunicationLink) As ServerCommunicationLink" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink -&gt; Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, communicationLinkName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-105">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-106">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-106">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de6ad-107">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-107">The required parameters for creating a server communication link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-108">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-108">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, communicationLinkName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-112">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-113">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-113">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de6ad-114">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-114">The required parameters for creating a server communication link.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de6ad-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de6ad-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-116">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-116">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerCommunicationLinksOperations, resourceGroupName As String, serverName As String, communicationLinkName As String, parameters As ServerCommunicationLink) As ServerCommunicationLink" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink -&gt; Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, communicationLinkName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-120">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-121">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-121">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de6ad-122">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-122">The required parameters for creating a server communication link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-123">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-123">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, communicationLinkName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-125">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-125">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-126">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-126">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-127">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-127">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-128">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-128">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de6ad-129">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-129">The required parameters for creating a server communication link.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de6ad-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de6ad-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-131">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-131">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServerCommunicationLinksOperations, resourceGroupName As String, serverName As String, communicationLinkName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.Delete (operations, resourceGroupName, serverName, communicationLinkName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-135">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-135">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-136">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-136">The name of the server communication link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-137">サーバーへの通信のリンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-137">Deletes a server communication link.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, communicationLinkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-139">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-140">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-141">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-141">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-142">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-142">The name of the server communication link.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de6ad-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de6ad-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-144">サーバーへの通信のリンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-144">Deletes a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink Get (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink Get(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerCommunicationLinksOperations, resourceGroupName As String, serverName As String, communicationLinkName As String) As ServerCommunicationLink" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.Get (operations, resourceGroupName, serverName, communicationLinkName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-146">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-146">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-147">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-148">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-148">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-149">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-149">The name of the server communication link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-150">サーバー通信リンクを返します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-150">Returns a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, string communicationLinkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, communicationLinkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-152">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-153">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-154">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-154">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="de6ad-155">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-155">The name of the server communication link.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de6ad-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de6ad-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-157">サーバー通信リンクを返します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-157">Returns a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; ListByServer (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt; ListByServer(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IServerCommunicationLinksOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of ServerCommunicationLink)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-159">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-160">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-161">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-161">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-162">サーバー通信リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-162">Gets a list of server communication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerCommunicationLinksOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de6ad-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de6ad-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de6ad-164">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="de6ad-165">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="de6ad-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="de6ad-166">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="de6ad-166">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de6ad-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de6ad-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de6ad-168">サーバー通信リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="de6ad-168">Gets a list of server communication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>