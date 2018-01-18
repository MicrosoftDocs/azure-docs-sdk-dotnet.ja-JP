<Type Name="LinkedServicesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LinkedServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LinkedServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LinkedServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LinkedServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7a3a4-101">LinkedServicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-101">Extension methods for LinkedServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.LinkedService CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.LinkedService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String, parameters As LinkedService) As LinkedService" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.LinkedService -&gt; Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.LinkedService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-103">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-103">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-105">LinkedServices リソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-105">Name of the Log Analytics Workspace that will contain the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-106">LinkedServices リソースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-106">Name of the linkedServices resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7a3a4-107">作成またはリンクされたサービスの更新に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-107">The parameters required to create or update a linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-108">作成またはリンクされたサービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-108">Create or update a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.LinkedService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.LinkedService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-110">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-110">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-111">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-112">LinkedServices リソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-112">Name of the Log Analytics Workspace that will contain the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-113">LinkedServices リソースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-113">Name of the linkedServices resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7a3a4-114">作成またはリンクされたサービスの更新に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-114">The parameters required to create or update a linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7a3a4-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-116">作成またはリンクされたサービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-116">Create or update a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-118">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-118">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-119">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-120">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-120">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-121">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-121">Name of the linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-122">リンクされたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-122">Deletes a linked service instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-124">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-124">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-125">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-126">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-126">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-127">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-127">Name of the linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7a3a4-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-129">リンクされたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-129">Deletes a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.LinkedService Get (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService Get(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String, linkedServiceName As String) As LinkedService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.LinkedService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-131">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-131">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-132">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-133">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-133">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-134">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-134">Name of the linked service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-135">リンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-135">Gets a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-137">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-137">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-138">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-139">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="7a3a4-139">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="7a3a4-140">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-140">Name of the linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7a3a4-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-142">リンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-142">Gets a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As ILinkedServicesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of LinkedService)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspace (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-144">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-144">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-145">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-145">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-146">リンクされたサービスを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-146">Name of the Log Analytics Workspace that contains the linked services.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-147">ワークスペースにリンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-147">Gets the linked services instances in a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions.ListByWorkspaceAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.LinkedServicesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7a3a4-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7a3a4-149">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-149">The name of the resource group to get.</span></span> <span data-ttu-id="7a3a4-150">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-150">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="7a3a4-151">リンクされたサービスを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-151">Name of the Log Analytics Workspace that contains the linked services.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7a3a4-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7a3a4-153">ワークスペースにリンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a3a4-153">Gets the linked services instances in a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>