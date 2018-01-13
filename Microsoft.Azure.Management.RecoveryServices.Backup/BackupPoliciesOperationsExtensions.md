<Type Name="BackupPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupPoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="47740-101">BackupPoliciesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="47740-101">Extension methods for BackupPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupPoliciesOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of ProtectionPolicyQueryObject) = null) As IPage(Of ProtectionPolicyResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="47740-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="47740-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="47740-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="47740-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="47740-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="47740-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="47740-105">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="47740-105">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47740-106">Recovery Services コンテナーに関連付けられているバックアップ ポリシーの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="47740-106">Lists of backup policies associated with Recovery Services Vault.</span></span> <span data-ttu-id="47740-107">API は、スコープを持つ結果を取得する改ページ調整パラメーターを提供します。</span><span class="sxs-lookup"><span data-stu-id="47740-107">API provides pagination parameters to fetch scoped results.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="47740-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="47740-108">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="47740-109">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="47740-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="47740-110">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="47740-110">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="47740-111">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="47740-111">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47740-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47740-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47740-113">Recovery Services コンテナーに関連付けられているバックアップ ポリシーの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="47740-113">Lists of backup policies associated with Recovery Services Vault.</span></span> <span data-ttu-id="47740-114">API は、スコープを持つ結果を取得する改ページ調整パラメーターを提供します。</span><span class="sxs-lookup"><span data-stu-id="47740-114">API provides pagination parameters to fetch scoped results.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupPoliciesOperations, nextPageLink As String) As IPage(Of ProtectionPolicyResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="47740-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="47740-115">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="47740-116">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="47740-116">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47740-117">Recovery Services コンテナーに関連付けられているバックアップ ポリシーの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="47740-117">Lists of backup policies associated with Recovery Services Vault.</span></span> <span data-ttu-id="47740-118">API は、スコープを持つ結果を取得する改ページ調整パラメーターを提供します。</span><span class="sxs-lookup"><span data-stu-id="47740-118">API provides pagination parameters to fetch scoped results.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupPoliciesOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="47740-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="47740-119">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="47740-120">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="47740-120">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47740-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47740-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47740-122">Recovery Services コンテナーに関連付けられているバックアップ ポリシーの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="47740-122">Lists of backup policies associated with Recovery Services Vault.</span></span> <span data-ttu-id="47740-123">API は、スコープを持つ結果を取得する改ページ調整パラメーターを提供します。</span><span class="sxs-lookup"><span data-stu-id="47740-123">API provides pagination parameters to fetch scoped results.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>