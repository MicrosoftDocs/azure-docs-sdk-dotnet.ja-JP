<Type Name="ManagersOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5d55-101">管理者の操作の拡張機能。</span><span class="sxs-lookup"><span data-stu-id="f5d55-101">The managers operations extensions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateExtendedInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo CreateExtendedInfo (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo CreateExtendedInfo(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateExtendedInfo(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateExtendedInfo (operations As IManagersOperations, parameters As ManagerExtendedInfo, resourceGroupName As String, managerName As String) As ManagerExtendedInfo" />
      <MemberSignature Language="F#" Value="static member CreateExtendedInfo : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateExtendedInfo (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-103">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-103">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-105">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-106">マネージャーの拡張情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-106">Creates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateExtendedInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; CreateExtendedInfoAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; CreateExtendedInfoAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateExtendedInfoAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateExtendedInfoAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateExtendedInfoAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;CreateExtendedInfoAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-107">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-108">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-108">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-109">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-109">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-110">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-110">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-112">マネージャーの拡張情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-112">Creates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Manager CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.Manager,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IManagersOperations, parameters As Manager, resourceGroupName As String, managerName As String) As Manager" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.Manager * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateOrUpdate (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Manager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-113">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-114">マネージャーです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-114">The manager.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-116">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-117">作成するか、マネージャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-117">Creates or updates the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.Manager,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.Manager * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.CreateOrUpdateAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-118">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-119">マネージャーです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-119">The manager.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-120">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-120">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-121">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-121">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-123">作成するか、マネージャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-123">Creates or updates the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IManagersOperations, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Delete (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-125">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-125">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-126">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-126">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-127">管理者を削除します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-127">Deletes the manager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;DeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-129">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-129">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-130">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-130">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-132">管理者を削除します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-132">Deletes the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteExtendedInfo">
      <MemberSignature Language="C#" Value="public static void DeleteExtendedInfo (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteExtendedInfo(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteExtendedInfo(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteExtendedInfo (operations As IManagersOperations, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteExtendedInfo : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteExtendedInfo (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-134">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-134">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-135">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-135">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-136">マネージャーの拡張情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-136">Deletes the extended info of the manager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteExtendedInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteExtendedInfoAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteExtendedInfoAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteExtendedInfoAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteExtendedInfoAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.DeleteExtendedInfoAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;DeleteExtendedInfoAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-138">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-138">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-139">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-139">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-141">マネージャーの拡張情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-141">Deletes the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Manager Get (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager Get(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IManagersOperations, resourceGroupName As String, managerName As String) As Manager" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Get (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Manager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-143">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-143">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-144">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-144">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-145">指定されたマネージャー名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-145">Returns the properties of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Key GetActivationKey (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Key GetActivationKey(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetActivationKey(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetActivationKey (operations As IManagersOperations, resourceGroupName As String, managerName As String) As Key" />
      <MemberSignature Language="F#" Value="static member GetActivationKey : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Key" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetActivationKey (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-148">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-149">マネージャーのアクティブ化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-149">Returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt; GetActivationKeyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt; GetActivationKeyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetActivationKeyAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetActivationKeyAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetActivationKeyAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetActivationKeyAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-151">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-151">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-152">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-152">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-154">マネージャーのアクティブ化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-154">Returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsymmetricEncryptedSecret">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret GetAsymmetricEncryptedSecret (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, string plainTextSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret GetAsymmetricEncryptedSecret(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, string plainTextSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetAsymmetricEncryptedSecret(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsymmetricEncryptedSecret (operations As IManagersOperations, resourceGroupName As String, managerName As String, plainTextSecret As String) As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="static member GetAsymmetricEncryptedSecret : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetAsymmetricEncryptedSecret (operations, resourceGroupName, managerName, plainTextSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="plainTextSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-155">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f5d55-155">The resource group name.</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-156">リソース名。</span><span class="sxs-lookup"><span data-stu-id="f5d55-156">The resource name.</span></span>
            </param>
        <param name="plainTextSecret">
            <span data-ttu-id="f5d55-157">プレーン テキストのシークレット。</span><span class="sxs-lookup"><span data-stu-id="f5d55-157">The plain text secret.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-158">このメソッドを使用して、ユーザーの機密情報 (ストレージ アカウント アクセス キー、ボリューム コンテナーの暗号化キーなど) を暗号化するには</span><span class="sxs-lookup"><span data-stu-id="f5d55-158">Use this method to encrypt the user secrets (Storage Account Access Key, Volume Container Encryption Key etc.)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5d55-159"><see cref="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />。</span><span class="sxs-lookup"><span data-stu-id="f5d55-159">The <see cref="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException" />
        <exception cref="T:System.InvalidOperationException" />
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-161">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-161">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-162">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-162">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-164">指定されたマネージャー名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-164">Returns the properties of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicePublicEncryptionKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey GetDevicePublicEncryptionKey (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey GetDevicePublicEncryptionKey(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDevicePublicEncryptionKey(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDevicePublicEncryptionKey (operations As IManagersOperations, deviceName As String, resourceGroupName As String, managerName As String) As PublicKey" />
      <MemberSignature Language="F#" Value="static member GetDevicePublicEncryptionKey : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDevicePublicEncryptionKey (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-165">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="f5d55-166">デバイス名</span><span class="sxs-lookup"><span data-stu-id="f5d55-166">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-167">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-167">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-168">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-168">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-169">デバイスの公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-169">Returns the public encryption key of the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicePublicEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt; GetDevicePublicEncryptionKeyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt; GetDevicePublicEncryptionKeyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDevicePublicEncryptionKeyAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDevicePublicEncryptionKeyAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDevicePublicEncryptionKeyAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetDevicePublicEncryptionKeyAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-170">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="f5d55-171">デバイス名</span><span class="sxs-lookup"><span data-stu-id="f5d55-171">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-172">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-172">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-173">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-173">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-175">デバイスの公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-175">Returns the public encryption key of the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceRegistrationKey">
      <MemberSignature Language="C#" Value="public static string GetDeviceRegistrationKey (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetDeviceRegistrationKey(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDeviceRegistrationKey(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDeviceRegistrationKey (operations As IManagersOperations, resourceGroupName As String, managerName As String) As String" />
      <MemberSignature Language="F#" Value="static member GetDeviceRegistrationKey : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetDeviceRegistrationKey (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-176">The operations group for this extension method.</span></span> 
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-177">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f5d55-177">The resource group name.</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-178">マネージャーの名前です。</span><span class="sxs-lookup"><span data-stu-id="f5d55-178">The manager name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-179">このメソッドを使用して、デバイスの登録に使用されることができる、登録キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-179">Use this method to fetch the Registration Key which can used for device registration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f5d55-180">デバイスの登録キー。</span><span class="sxs-lookup"><span data-stu-id="f5d55-180">The device registration key.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEncryptionSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings GetEncryptionSettings (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings GetEncryptionSettings(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetEncryptionSettings(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetEncryptionSettings (operations As IManagersOperations, resourceGroupName As String, managerName As String) As EncryptionSettings" />
      <MemberSignature Language="F#" Value="static member GetEncryptionSettings : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetEncryptionSettings (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-182">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-182">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-183">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-183">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-184">マネージャーの暗号化の設定を返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-184">Returns the encryption settings of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEncryptionSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt; GetEncryptionSettingsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt; GetEncryptionSettingsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetEncryptionSettingsAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetEncryptionSettingsAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetEncryptionSettingsAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetEncryptionSettingsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-186">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-186">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-187">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-187">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-189">マネージャーの暗号化の設定を返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-189">Returns the encryption settings of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExtendedInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo GetExtendedInfo (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo GetExtendedInfo(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetExtendedInfo(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetExtendedInfo (operations As IManagersOperations, resourceGroupName As String, managerName As String) As ManagerExtendedInfo" />
      <MemberSignature Language="F#" Value="static member GetExtendedInfo : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetExtendedInfo (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-191">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-191">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-192">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-192">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-193">指定されたマネージャー名の拡張情報を返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-193">Returns the extended information of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExtendedInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; GetExtendedInfoAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; GetExtendedInfoAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetExtendedInfoAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetExtendedInfoAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetExtendedInfoAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetExtendedInfoAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-195">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-195">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-196">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-196">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-198">指定されたマネージャー名の拡張情報を返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-198">Returns the extended information of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublicEncryptionKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret GetPublicEncryptionKey (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret GetPublicEncryptionKey(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetPublicEncryptionKey(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPublicEncryptionKey (operations As IManagersOperations, resourceGroupName As String, managerName As String) As SymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="static member GetPublicEncryptionKey : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetPublicEncryptionKey (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-200">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-200">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-201">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-201">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-202">マネージャーの対称の暗号化された公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-202">Returns the symmetric encrypted public encryption key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublicEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt; GetPublicEncryptionKeyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt; GetPublicEncryptionKeyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetPublicEncryptionKeyAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPublicEncryptionKeyAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.GetPublicEncryptionKeyAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;GetPublicEncryptionKeyAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-203">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-204">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-204">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-205">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-205">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-207">マネージャーの対称の暗号化された公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-207">Returns the symmetric encrypted public encryption key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; List (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; List(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.List(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IManagersOperations) As IEnumerable(Of Manager)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-208">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-209">サブスクリプション内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-209">Retrieves all the managers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; ListAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; ListAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-210">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-212">サブスクリプション内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-212">Retrieves all the managers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; ListByResourceGroup (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; ListByResourceGroup(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IManagersOperations, resourceGroupName As String) As IEnumerable(Of Manager)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-214">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-214">The resource group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-215">リソース グループ内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-215">Retrieves all the managers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-217">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-217">The resource group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-219">リソース グループ内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-219">Retrieves all the managers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFeatureSupportStatus">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt; ListFeatureSupportStatus (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt; ListFeatureSupportStatus(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListFeatureSupportStatus(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFeatureSupportStatus (operations As IManagersOperations, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of FeatureFilter) = null) As IEnumerable(Of Feature)" />
      <MemberSignature Language="F#" Value="static member ListFeatureSupportStatus : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListFeatureSupportStatus (operations, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-221">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-221">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-222">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-222">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f5d55-223">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5d55-223">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-224">機能とサポートの状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-224">Lists the features and their support status</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFeatureSupportStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt; ListFeatureSupportStatusAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt; ListFeatureSupportStatusAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListFeatureSupportStatusAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFeatureSupportStatusAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListFeatureSupportStatusAsync (operations, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;ListFeatureSupportStatusAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-226">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-226">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-227">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-227">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f5d55-228">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5d55-228">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-229">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-230">機能とサポートの状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-230">Lists the features and their support status</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IManagersOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricDefinition (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-232">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-232">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-233">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-233">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-234">指定したマネージャーのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-234">Gets the metric definitions for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricDefinitionAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-236">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-236">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-237">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-237">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-239">指定したマネージャーのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-239">Gets the metric definitions for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IManagersOperations, odataQuery As ODataQuery(Of MetricFilter), resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetrics (operations, odataQuery, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-240">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f5d55-241">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5d55-241">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-242">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-242">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-243">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-243">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-244">指定したマネージャーのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-244">Gets the metrics for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.ListMetricsAsync (operations, odataQuery, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;ListMetricsAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-245">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f5d55-246">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="f5d55-246">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-247">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-247">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-248">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-248">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-250">指定したマネージャーのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-250">Gets the metrics for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateActivationKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Key RegenerateActivationKey (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Key RegenerateActivationKey(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.RegenerateActivationKey(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateActivationKey (operations As IManagersOperations, resourceGroupName As String, managerName As String) As Key" />
      <MemberSignature Language="F#" Value="static member RegenerateActivationKey : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Key" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.RegenerateActivationKey (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Key</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-251">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-252">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-252">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-253">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-253">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-254">再生成し、マネージャーのライセンス認証キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-254">Re-generates and returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateActivationKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt; RegenerateActivationKeyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt; RegenerateActivationKeyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.RegenerateActivationKeyAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateActivationKeyAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.RegenerateActivationKeyAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;RegenerateActivationKeyAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-256">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-256">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-257">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-257">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-259">再生成し、マネージャーのライセンス認証キーを返します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-259">Re-generates and returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Manager Update (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager Update(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Update(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IManagersOperations, parameters As ManagerPatch, resourceGroupName As String, managerName As String) As Manager" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.Update (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Manager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-260">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-261">管理者は、パラメーターを更新できます。</span><span class="sxs-lookup"><span data-stu-id="f5d55-261">The manager update parameters.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-262">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-262">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-263">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-263">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-264">StorSimple Manager を更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-264">Updates the StorSimple Manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; UpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt; UpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;UpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-265">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-266">管理者は、パラメーターを更新できます。</span><span class="sxs-lookup"><span data-stu-id="f5d55-266">The manager update parameters.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-267">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-267">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-268">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-268">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-270">StorSimple Manager を更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-270">Updates the StorSimple Manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtendedInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo UpdateExtendedInfo (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo UpdateExtendedInfo(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateExtendedInfo(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateExtendedInfo (operations As IManagersOperations, parameters As ManagerExtendedInfo, resourceGroupName As String, managerName As String, ifMatch As String) As ManagerExtendedInfo" />
      <MemberSignature Language="F#" Value="static member UpdateExtendedInfo : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateExtendedInfo (operations, parameters, resourceGroupName, managerName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-271">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-272">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-272">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-273">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-273">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-274">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-274">The manager name</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="f5d55-275">GET 呼び出しから現在フェッチ ExtendedInfo の ETag を渡す</span><span class="sxs-lookup"><span data-stu-id="f5d55-275">Pass the ETag of ExtendedInfo fetched from GET call</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-276">マネージャーの拡張情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-276">Updates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtendedInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; UpdateExtendedInfoAsync (this Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt; UpdateExtendedInfoAsync(class Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateExtendedInfoAsync(Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateExtendedInfoAsync : Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions.UpdateExtendedInfoAsync (operations, parameters, resourceGroupName, managerName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.ManagersOperationsExtensions/&lt;UpdateExtendedInfoAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f5d55-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f5d55-277">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f5d55-278">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-278">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f5d55-279">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f5d55-279">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f5d55-280">管理者名</span><span class="sxs-lookup"><span data-stu-id="f5d55-280">The manager name</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="f5d55-281">GET 呼び出しから現在フェッチ ExtendedInfo の ETag を渡す</span><span class="sxs-lookup"><span data-stu-id="f5d55-281">Pass the ETag of ExtendedInfo fetched from GET call</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f5d55-282">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f5d55-282">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f5d55-283">マネージャーの拡張情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="f5d55-283">Updates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>