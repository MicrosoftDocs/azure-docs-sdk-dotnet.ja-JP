<Type Name="ApplicationOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d946-101">ApplicationOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="9d946-101">Extension methods for ApplicationOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Application Create (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Application Create(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String, Optional parameters As ApplicationCreateParameters = null) As Application" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.Application" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Create (operations, resourceGroupName, accountName, applicationId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Application</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-103">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-104">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-104">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-105">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-105">The ID of the application.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d946-106">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9d946-106">The parameters for the request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-107">指定したバッチ アカウントにアプリケーションを追加します。</span><span class="sxs-lookup"><span data-stu-id="9d946-107">Adds an application to the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, applicationId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-109">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-109">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-110">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-110">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-111">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-111">The ID of the application.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d946-112">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9d946-112">The parameters for the request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-114">指定したバッチ アカウントにアプリケーションを追加します。</span><span class="sxs-lookup"><span data-stu-id="9d946-114">Adds an application to the specified Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Delete (operations, resourceGroupName, accountName, applicationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-116">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-116">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-117">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-117">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-118">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-118">The ID of the application.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-119">アプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="9d946-119">Deletes an application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, applicationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-121">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-121">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-122">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-122">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-123">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-123">The ID of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-125">アプリケーションを削除します。</span><span class="sxs-lookup"><span data-stu-id="9d946-125">Deletes an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Application Get (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Application Get(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String) As Application" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Application" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Get (operations, resourceGroupName, accountName, applicationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Application</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-127">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-127">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-128">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-128">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-129">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-129">The ID of the application.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-130">指定されたアプリケーションに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d946-130">Gets information about the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; GetAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; GetAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, applicationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-132">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-132">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-133">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-133">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-134">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-134">The ID of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-136">指定されたアプリケーションに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d946-136">Gets information about the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; List (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; List(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.List(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IApplicationOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null) As IPage(Of Application)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.List (operations, resourceGroupName, accountName, maxresults)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-138">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-138">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-139">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-139">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="9d946-140">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="9d946-140">The maximum number of items to return in the response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-141">すべての指定されたアカウントでアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d946-141">Lists all of the applications in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListAsync (operations, resourceGroupName, accountName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-143">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-143">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-144">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-144">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="9d946-145">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="9d946-145">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-147">すべての指定されたアカウントでアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d946-147">Lists all of the applications in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; ListNext (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; ListNext(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNext(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IApplicationOperations, nextPageLink As String) As IPage(Of Application)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Batch.IApplicationOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-148">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d946-149">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9d946-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-150">すべての指定されたアカウントでアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d946-150">Lists all of the applications in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-151">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="9d946-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9d946-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-154">すべての指定されたアカウントでアプリケーションの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9d946-154">Lists all of the applications in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String, parameters As ApplicationUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Update (operations, resourceGroupName, accountName, applicationId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-156">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-156">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-157">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-157">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-158">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-158">The ID of the application.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d946-159">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9d946-159">The parameters for the request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-160">指定したアプリケーションの設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="9d946-160">Updates settings for the specified application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, applicationId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9d946-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="9d946-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9d946-162">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-162">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="9d946-163">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d946-163">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="9d946-164">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="9d946-164">The ID of the application.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9d946-165">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="9d946-165">The parameters for the request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9d946-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9d946-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9d946-167">指定したアプリケーションの設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="9d946-167">Updates settings for the specified application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>