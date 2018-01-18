<Type Name="AccessControlRecordsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AccessControlRecordsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AccessControlRecordsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AccessControlRecordsOperationsExtensions = class" />
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
            <span data-ttu-id="faa71-101">AccessControlRecordsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="faa71-101">Extension methods for AccessControlRecordsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IAccessControlRecordsOperations, accessControlRecordName As String, parameters As AccessControlRecord, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdate (operations, accessControlRecordName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-103">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-103">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="faa71-104">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="faa71-104">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-105">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-106">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-106">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-107">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="faa71-107">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginCreateOrUpdateAsync (operations, accessControlRecordName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-108">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-109">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-109">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="faa71-110">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="faa71-110">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-111">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-111">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-112">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-112">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-114">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="faa71-114">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDelete (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-115">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-116">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-116">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-117">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-118">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-118">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-119">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="faa71-119">Deletes the access control record.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.BeginDeleteAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-120">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-121">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-121">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-122">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-123">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-123">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-125">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="faa71-125">Deletes the access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAccessControlRecordsOperations, accessControlRecordName As String, parameters As AccessControlRecord, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdate (operations, accessControlRecordName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-126">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-127">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-127">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="faa71-128">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="faa71-128">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-129">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-129">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-130">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-130">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-131">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="faa71-131">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.CreateOrUpdateAsync (operations, accessControlRecordName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-132">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-133">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-133">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="faa71-134">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="faa71-134">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-135">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-136">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-136">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-138">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="faa71-138">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Delete (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-139">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-140">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-140">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-141">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-141">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-142">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-142">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-143">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="faa71-143">Deletes the access control record.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.DeleteAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-144">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-145">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="faa71-145">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-146">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-146">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-147">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-147">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-149">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="faa71-149">Deletes the access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord Get (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord Get(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAccessControlRecordsOperations, accessControlRecordName As String, resourceGroupName As String, managerName As String) As AccessControlRecord" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.Get (operations, accessControlRecordName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-150">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-151">取得するアクセス制御レコードの名前です。</span><span class="sxs-lookup"><span data-stu-id="faa71-151">Name of access control record to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-152">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-152">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-153">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-153">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-154">指定したアクセス制御レコード名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="faa71-154">Returns the properties of the specified access control record name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string accessControlRecordName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.GetAsync (operations, accessControlRecordName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-155">The operations group for this extension method.</span></span>
            </param>
        <param name="accessControlRecordName">
            <span data-ttu-id="faa71-156">取得するアクセス制御レコードの名前です。</span><span class="sxs-lookup"><span data-stu-id="faa71-156">Name of access control record to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-157">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-157">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-158">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-158">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-160">指定したアクセス制御レコード名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="faa71-160">Returns the properties of the specified access control record name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IAccessControlRecordsOperations, resourceGroupName As String, managerName As String) As IEnumerable(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-162">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-163">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-163">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-164">マネージャー内のすべてのアクセス制御レコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="faa71-164">Retrieves all the access control records in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations operations, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AccessControlRecordsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="faa71-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="faa71-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="faa71-166">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="faa71-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="faa71-167">管理者名</span><span class="sxs-lookup"><span data-stu-id="faa71-167">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="faa71-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="faa71-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="faa71-169">マネージャー内のすべてのアクセス制御レコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="faa71-169">Retrieves all the access control records in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>