<Type Name="FileServersOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileServersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f0204-101">FileServersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f0204-101">Extension methods for FileServersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer BeginCreate (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer BeginCreate(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String, parameters As FileServerCreateParameters) As FileServer" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreate (operations, resourceGroupName, fileServerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-104">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-104">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-105">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-105">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-106">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-106">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0204-107">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f0204-107">The parameters to provide for file server creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-108">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="f0204-108">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, fileServerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-111">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-111">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-112">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-112">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-113">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-113">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0204-114">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f0204-114">The parameters to provide for file server creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-116">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="f0204-116">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDelete (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-118">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-118">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-119">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-119">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-120">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-120">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-121">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-121">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-122">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="f0204-122">Delete a file Server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-124">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-124">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-125">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-125">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-126">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-126">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-127">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-127">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-129">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="f0204-129">Delete a file Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer Create (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer Create(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String, parameters As FileServerCreateParameters) As FileServer" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Create (operations, resourceGroupName, fileServerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-132">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-132">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-133">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-133">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-134">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-134">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0204-135">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f0204-135">The parameters to provide for file server creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-136">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="f0204-136">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.CreateAsync (operations, resourceGroupName, fileServerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-138">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-138">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-139">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-139">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-140">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-140">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-141">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-141">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0204-142">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f0204-142">The parameters to provide for file server creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-144">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="f0204-144">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Delete (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-146">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-147">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-147">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-148">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-148">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-149">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-149">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-150">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="f0204-150">Delete a file Server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-152">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-152">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-153">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-153">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-154">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-154">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-155">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-155">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-157">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="f0204-157">Delete a file Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer Get (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer Get(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String) As FileServer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Get (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-160">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-160">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-161">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-161">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-162">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-162">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-163">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-163">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.GetAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-165">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-165">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="f0204-166">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f0204-166">The name of the file server within the specified resource group.</span></span> <span data-ttu-id="f0204-167">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="f0204-167">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="f0204-168">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f0204-168">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-170">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-170">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; List (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; List(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IFileServersOperations,Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IFileServersOperations * Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.List (operations, fileServersListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="fileServersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-171">The operations group for this extension method.</span></span>
            </param>
        <param name="fileServersListOptions">
            <span data-ttu-id="f0204-172">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f0204-172">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-173">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="f0204-173">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListAsync (operations, fileServersListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="fileServersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-174">The operations group for this extension method.</span></span>
            </param>
        <param name="fileServersListOptions">
            <span data-ttu-id="f0204-175">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f0204-175">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-177">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="f0204-177">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, fileServersListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-179">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-179">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServersListByResourceGroupOptions">
            <span data-ttu-id="f0204-180">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f0204-180">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-181">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-181">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, fileServersListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0204-183">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="f0204-183">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServersListByResourceGroupOptions">
            <span data-ttu-id="f0204-184">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="f0204-184">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-186">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-186">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IFileServersOperations, nextPageLink As String) As IPage(Of FileServer)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-187">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0204-188">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f0204-188">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-189">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-189">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-190">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0204-191">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f0204-191">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-193">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0204-193">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFileServersOperations, nextPageLink As String) As IPage(Of FileServer)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0204-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f0204-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-196">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="f0204-196">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0204-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f0204-197">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0204-198">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f0204-198">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0204-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f0204-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0204-200">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="f0204-200">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>