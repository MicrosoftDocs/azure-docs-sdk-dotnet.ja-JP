<Type Name="ApplicationPackageOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationPackageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationPackageOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f842c-101">ApplicationPackageOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f842c-101">Extension methods for ApplicationPackageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ActivateAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ActivateAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, class Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.ActivateAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ActivateAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.ActivateAsync (operations, resourceGroupName, accountName, applicationId, version, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;ActivateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="accountName">To be added.</param>
        <param name="applicationId">To be added.</param>
        <param name="version">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; CreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; CreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f842c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f842c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f842c-103">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f842c-104">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-104">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="f842c-105">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="f842c-105">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="f842c-106">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="f842c-106">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f842c-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f842c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f842c-108">アプリケーション パッケージ レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="f842c-108">Creates an application package record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f842c-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f842c-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f842c-110">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-110">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f842c-111">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-111">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="f842c-112">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="f842c-112">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="f842c-113">削除するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="f842c-113">The version of the application to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f842c-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f842c-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f842c-115">アプリケーション パッケージ レコードとそれに関連付けられているバイナリ ファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="f842c-115">Deletes an application package record and its associated binary file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; GetAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; GetAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f842c-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f842c-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f842c-117">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-117">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f842c-118">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f842c-118">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="f842c-119">アプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="f842c-119">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="f842c-120">アプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="f842c-120">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f842c-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f842c-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f842c-122">指定されたアプリケーション パッケージに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f842c-122">Gets information about the specified application package.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>