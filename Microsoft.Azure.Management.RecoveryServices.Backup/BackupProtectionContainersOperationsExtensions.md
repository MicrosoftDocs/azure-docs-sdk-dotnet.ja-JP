<Type Name="BackupProtectionContainersOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupProtectionContainersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupProtectionContainersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupProtectionContainersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupProtectionContainersOperationsExtensions = class" />
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
            <span data-ttu-id="ef85e-101">BackupProtectionContainersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="ef85e-101">Extension methods for BackupProtectionContainersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IBackupProtectionContainersOperations, vaultName As String, resourceGroupName As String, Optional odataQuery As ODataQuery(Of BMSContainerQueryObject) = null) As IPage(Of ProtectionContainerResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.List (operations, vaultName, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef85e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ef85e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ef85e-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="ef85e-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef85e-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ef85e-105">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ef85e-105">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef85e-106">Recovery Services コンテナーに登録されているコンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-106">Lists the containers registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string vaultName, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string vaultName, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef85e-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ef85e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="ef85e-108">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="ef85e-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ef85e-109">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-109">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ef85e-110">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ef85e-110">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef85e-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ef85e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef85e-112">Recovery Services コンテナーに登録されているコンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-112">Lists the containers registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IBackupProtectionContainersOperations, nextPageLink As String) As IPage(Of ProtectionContainerResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef85e-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ef85e-113">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ef85e-114">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ef85e-114">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef85e-115">Recovery Services コンテナーに登録されているコンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-115">Lists the containers registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupProtectionContainersOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupProtectionContainersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ef85e-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="ef85e-116">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ef85e-117">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ef85e-117">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ef85e-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ef85e-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ef85e-119">Recovery Services コンテナーに登録されているコンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ef85e-119">Lists the containers registered to Recovery Services Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>