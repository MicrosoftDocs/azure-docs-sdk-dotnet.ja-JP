<Type Name="ApplicationPackageOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationPackageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationPackageOperationsExtensions = class" />
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
            <span data-ttu-id="49f59-101">ApplicationPackageOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="49f59-101">Extension methods for ApplicationPackageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Activate">
      <MemberSignature Language="C#" Value="public static void Activate (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, string format);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Activate(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Activate(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Activate (operations As IApplicationPackageOperations, resourceGroupName As String, accountName As String, applicationId As String, version As String, format As String)" />
      <MemberSignature Language="F#" Value="static member Activate : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Activate (operations, resourceGroupName, accountName, applicationId, version, format)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-103">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-104">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-104">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-105">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-105">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-106">アクティブ化するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-106">The version of the application to activate.</span></span>
            </param>
        <param name="format">
            <span data-ttu-id="49f59-107">アプリケーション パッケージのバイナリ ファイルの形式です。</span><span class="sxs-lookup"><span data-stu-id="49f59-107">The format of the application package binary file.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-108">指定したアプリケーション パッケージをアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="49f59-108">Activates the specified application package.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ActivateAsync (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, string format, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ActivateAsync(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, string format, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.ActivateAsync(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ActivateAsync : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.ActivateAsync (operations, resourceGroupName, accountName, applicationId, version, format, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions/&lt;ActivateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-110">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-110">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-111">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-111">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-112">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-112">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-113">アクティブ化するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-113">The version of the application to activate.</span></span>
            </param>
        <param name="format">
            <span data-ttu-id="49f59-114">アプリケーション パッケージのバイナリ ファイルの形式です。</span><span class="sxs-lookup"><span data-stu-id="49f59-114">The format of the application package binary file.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="49f59-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="49f59-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-116">指定したアプリケーション パッケージをアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="49f59-116">Activates the specified application package.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.ApplicationPackage Create (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.ApplicationPackage Create(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IApplicationPackageOperations, resourceGroupName As String, accountName As String, applicationId As String, version As String) As ApplicationPackage" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationPackage" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Create (operations, resourceGroupName, accountName, applicationId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ApplicationPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-118">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-118">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-119">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-119">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-120">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-120">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-121">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-121">The version of the application.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-122">アプリケーション パッケージ レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="49f59-122">Creates an application package record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-124">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-124">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-125">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-125">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-126">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-126">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-127">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-127">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="49f59-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="49f59-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-129">アプリケーション パッケージ レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="49f59-129">Creates an application package record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IApplicationPackageOperations, resourceGroupName As String, accountName As String, applicationId As String, version As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Delete (operations, resourceGroupName, accountName, applicationId, version)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-131">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-131">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-132">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-132">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-133">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-133">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-134">削除するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-134">The version of the application to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-135">アプリケーション パッケージ レコードとそれに関連付けられているバイナリ ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="49f59-135">Deletes an application package record and its associated binary file.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-137">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-137">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-138">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-138">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-139">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-139">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-140">削除するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-140">The version of the application to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="49f59-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="49f59-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-142">アプリケーション パッケージ レコードとそれに関連付けられているバイナリ ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="49f59-142">Deletes an application package record and its associated binary file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.ApplicationPackage Get (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.ApplicationPackage Get(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IApplicationPackageOperations, resourceGroupName As String, accountName As String, applicationId As String, version As String) As ApplicationPackage" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationPackage" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.Get (operations, resourceGroupName, accountName, applicationId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ApplicationPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-144">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-144">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-145">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-145">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-146">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-146">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-147">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-147">The version of the application.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-148">指定されたアプリケーション パッケージに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="49f59-148">Gets information about the specified application package.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; GetAsync (this Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; GetAsync(class Microsoft.Azure.Management.Batch.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationPackageOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="49f59-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="49f59-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="49f59-150">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-150">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="49f59-151">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="49f59-151">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="49f59-152">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="49f59-152">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="49f59-153">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="49f59-153">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="49f59-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="49f59-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49f59-155">指定されたアプリケーション パッケージに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="49f59-155">Gets information about the specified application package.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>