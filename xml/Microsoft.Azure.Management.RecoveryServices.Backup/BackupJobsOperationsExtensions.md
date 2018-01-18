<Type Name="BackupJobsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupJobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupJobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupJobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupJobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5acbb-101">BackupJobsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5acbb-101">Extension methods for BackupJobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery = null, string skipToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery, string skipToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupJobsOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of JobQueryObject) = null, Optional skipToken As String = null) As IPage(Of JobResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery, skipToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5acbb-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5acbb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="5acbb-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="5acbb-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5acbb-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5acbb-105">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5acbb-105">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="5acbb-106">skipToken フィルター。</span><span class="sxs-lookup"><span data-stu-id="5acbb-106">skipToken Filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5acbb-107">ジョブのページング可能な一覧を提供します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-107">Provides a pageable list of jobs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery = null, string skipToken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; odataQuery, string skipToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, skipToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject&gt;" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5acbb-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5acbb-108">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="5acbb-109">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="5acbb-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5acbb-110">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-110">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5acbb-111">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5acbb-111">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="5acbb-112">skipToken フィルター。</span><span class="sxs-lookup"><span data-stu-id="5acbb-112">skipToken Filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5acbb-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5acbb-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5acbb-114">ジョブのページング可能な一覧を提供します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-114">Provides a pageable list of jobs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupJobsOperations, nextPageLink As String) As IPage(Of JobResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5acbb-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5acbb-115">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5acbb-116">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5acbb-116">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5acbb-117">ジョブのページング可能な一覧を提供します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-117">Provides a pageable list of jobs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupJobsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5acbb-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5acbb-118">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5acbb-119">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5acbb-119">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5acbb-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5acbb-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5acbb-121">ジョブのページング可能な一覧を提供します。</span><span class="sxs-lookup"><span data-stu-id="5acbb-121">Provides a pageable list of jobs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>