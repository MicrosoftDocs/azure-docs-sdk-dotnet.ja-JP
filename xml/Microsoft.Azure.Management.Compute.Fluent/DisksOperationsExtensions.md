<Type Name="DisksOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DisksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DisksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DisksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DisksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9cb8-101">DisksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-101">Extension methods for DisksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-103">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-104">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-104">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c9cb8-105">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-105">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-107">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-107">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-109">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-110">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-110">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-112">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-112">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-114">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-115">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-115">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c9cb8-116">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-116">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-118">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-118">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-120">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-121">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-121">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-123">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-123">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;BeginUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-125">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-126">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-126">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c9cb8-127">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-127">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-129">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-129">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-131">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-132">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-132">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c9cb8-133">ディスクの Put 操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-133">Disk object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-135">作成するか、ディスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-135">Creates or updates a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.DeleteAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-137">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-137">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-138">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-138">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-140">ディスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-140">Deletes a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GetAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-142">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-143">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-143">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-145">ディスクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-145">Gets information about a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, diskName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;GrantAccessAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-147">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-148">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-148">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="c9cb8-149">ディスク アクセスの取得操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-149">Access data object supplied in the body of the get disk access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-151">ディスクへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-151">Grants access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-152">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-154">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-154">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-156">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-158">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-158">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c9cb8-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-162">リソース グループの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-162">Lists all the disks under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c9cb8-164">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-166">サブスクリプションの下のすべてのディスクを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-166">Lists all the disks under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, diskName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;RevokeAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-168">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-168">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-169">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-169">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-171">ディスクへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-171">Revokes access to a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations operations, string resourceGroupName, string diskName, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner disk, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IDisksOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions.UpdateAsync (operations, resourceGroupName, diskName, disk, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.DisksOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="diskName" Type="System.String" />
        <Parameter Name="disk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c9cb8-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c9cb8-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-173">The name of the resource group.</span></span>
            </param>
        <param name="diskName">
            <span data-ttu-id="c9cb8-174">指定されたサブスクリプションとリソース グループ内のディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-174">The name of the disk within the given subscription and resource group.</span></span>
            </param>
        <param name="disk">
            <span data-ttu-id="c9cb8-175">修正プログラムのディスク操作の本文に指定されているディスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-175">Disk object supplied in the body of the Patch disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9cb8-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9cb8-177">更新プログラム (修正プログラム) ディスクです。</span><span class="sxs-lookup"><span data-stu-id="c9cb8-177">Updates (patches) a disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>