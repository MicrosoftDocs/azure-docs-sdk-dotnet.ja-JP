<Type Name="DisksOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.DisksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DisksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DisksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.DisksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DisksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DisksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c94c5-101">DisksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c94c5-101">Extension methods for DisksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Disk BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.Disk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Disk BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.Disk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Disk)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.Disk -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, diskName, disk)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Disk</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.Disk" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-103">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-104">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-104">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-105">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-105">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-106">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-106">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.Disk disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.Disk disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Disk,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.Disk * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.Disk" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-108">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-109">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-109">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-110">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-110">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-112">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-112">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IDisksOperations, resourceGroupName As String, diskName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IDisksOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginDelete (operations, resourceGroupName, diskName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-114">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-115">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-115">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-116">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-116">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-118">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-119">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-119">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-121">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-121">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginGrantAccess(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccess : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginGrantAccess (operations, resourceGroupName, diskName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-123">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-124">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-124">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c94c5-125">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-125">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-126">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-126">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-128">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-129">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-129">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c94c5-130">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-130">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-132">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-132">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginRevokeAccess(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRevokeAccess (operations As IDisksOperations, resourceGroupName As String, diskName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccess : Microsoft.Azure.Management.Compute.IDisksOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginRevokeAccess (operations, resourceGroupName, diskName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-134">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-135">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-135">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-136">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-136">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-138">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-139">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-139">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-141">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-141">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Disk BeginUpdate (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.DiskUpdate disk);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Disk BeginUpdate(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.DiskUpdate disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.DiskUpdate)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.DiskUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginUpdate (operations, resourceGroupName, diskName, disk)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Disk</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.DiskUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-143">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-144">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-144">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-145">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-145">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-146">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-146">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.DiskUpdate disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.DiskUpdate disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.DiskUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.DiskUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.DiskUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-148">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-149">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-149">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-150">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-150">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-152">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-152">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Disk CreateOrUpdate (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.Disk disk);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Disk CreateOrUpdate(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.Disk disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Disk)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.Disk -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, diskName, disk)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Disk</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.Disk" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-154">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-155">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-155">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-156">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-156">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-157">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-157">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.Disk disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.Disk disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Disk,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.Disk * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.Disk" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-159">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-160">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-160">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-161">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-161">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-163">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-163">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDisksOperations, resourceGroupName As String, diskName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IDisksOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Delete (operations, resourceGroupName, diskName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-165">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-166">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-166">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-167">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-167">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.DeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-169">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-170">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-170">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-172">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-172">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Disk Get (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Disk Get(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDisksOperations, resourceGroupName As String, diskName As String) As Disk" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IDisksOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Get (operations, resourceGroupName, diskName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Disk</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-174">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-174">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-175">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-175">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-176">ディスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-176">Gets information about a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; GetAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; GetAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GetAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-178">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-179">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-179">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-181">ディスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-181">Gets information about a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GrantAccess(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member GrantAccess : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GrantAccess (operations, resourceGroupName, diskName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-183">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-184">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-184">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c94c5-185">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-185">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-186">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-186">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;GrantAccessAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-188">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-188">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-189">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-189">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c94c5-190">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-190">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-192">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-192">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; List (this Microsoft.Azure.Management.Compute.IDisksOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; List(class Microsoft.Azure.Management.Compute.IDisksOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.List(Microsoft.Azure.Management.Compute.IDisksOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDisksOperations) As IPage(Of Disk)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IDisksOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-193">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-194">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-194">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IDisksOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-195">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-197">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-197">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.IDisksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IDisksOperations, resourceGroupName As String) As IPage(Of Disk)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.IDisksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-199">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-200">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-200">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-202">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-204">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-204">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.IDisksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IDisksOperations, nextPageLink As String) As IPage(Of Disk)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.IDisksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c94c5-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c94c5-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-207">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-207">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c94c5-209">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c94c5-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-211">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-211">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; ListNext (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; ListNext(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IDisksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDisksOperations, nextPageLink As String) As IPage(Of Disk)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IDisksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c94c5-213">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c94c5-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-214">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-214">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c94c5-216">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c94c5-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-218">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-218">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.RevokeAccess(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RevokeAccess (operations As IDisksOperations, resourceGroupName As String, diskName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member RevokeAccess : Microsoft.Azure.Management.Compute.IDisksOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.RevokeAccess (operations, resourceGroupName, diskName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-220">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-220">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-221">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-221">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-222">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-222">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;RevokeAccessAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-224">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-224">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-225">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-225">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-227">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c94c5-227">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Disk Update (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.DiskUpdate disk);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Disk Update(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.DiskUpdate disk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Update(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.DiskUpdate)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.DiskUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.Update (operations, resourceGroupName, diskName, disk)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Disk</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.DiskUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-229">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-229">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-230">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-230">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-231">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-231">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-232">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-232">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Models.DiskUpdate disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Disk&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Models.DiskUpdate disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.DisksOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.DiskUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Models.DiskUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;" Usage="Microsoft.Azure.Management.Compute.DisksOperationsExtensions.UpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.DisksOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Disk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Models.DiskUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c94c5-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c94c5-234">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-234">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c94c5-235">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c94c5-235">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c94c5-236">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c94c5-236">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c94c5-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c94c5-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c94c5-238">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c94c5-238">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>