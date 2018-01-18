<Type Name="DeploymentsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7b2e-101">DeploymentsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-101">Extension methods for DeploymentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-103">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-104">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-105">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-105">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7b2e-106">追加のパラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-106">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-108">テンプレートを使用して名前付きテンプレートのデプロイを作成します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-108">Create a named template deployment using a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-110">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-111">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-111">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-112">削除するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-112">The name of the deployment to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-114">展開を削除します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-114">Delete deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CancelAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CancelAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CancelAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-116">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-117">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-117">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-118">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-118">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-120">現在実行中のテンプレート デプロイをキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-120">Cancel a currently running template deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-122">確認するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-122">The name of the resource group to check.</span></span> <span data-ttu-id="f7b2e-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-123">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-124">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-124">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-126">展開が存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-126">Checks whether deployment exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-128">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-129">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-129">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-130">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-130">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7b2e-131">追加のパラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-131">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-133">テンプレートを使用して名前付きテンプレートのデプロイを作成します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-133">Create a named template deployment using a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-135">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-136">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-136">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-137">削除するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-137">The name of the deployment to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-139">展開を削除します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-139">Delete deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExportResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-141">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-142">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-142">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-143">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-143">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-145">展開テンプレートをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-145">Exports a deployment template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-147">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-147">The name of the resource group to get.</span></span> <span data-ttu-id="f7b2e-148">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-148">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-149">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-149">The name of the deployment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-151">展開を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-151">Get a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-153">フィルター処理するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-153">The name of the resource group to filter by.</span></span> <span data-ttu-id="f7b2e-154">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-154">The name is case insensitive.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f7b2e-155">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-155">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-157">展開の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-157">Get a list of deployments.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentExtendedInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-158">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f7b2e-159">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-159">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-161">展開の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-161">Get a list of deployments.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt; ValidateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt; ValidateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations operations, string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ValidateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions.ValidateAsync (operations, resourceGroupName, deploymentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.DeploymentsOperationsExtensions/&lt;ValidateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentValidateResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f7b2e-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f7b2e-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-163">The name of the resource group.</span></span> <span data-ttu-id="f7b2e-164">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-164">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="f7b2e-165">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-165">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7b2e-166">検証するデプロイ。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-166">Deployment to validate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b2e-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b2e-168">展開テンプレートを検証します。</span><span class="sxs-lookup"><span data-stu-id="f7b2e-168">Validate a deployment template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>