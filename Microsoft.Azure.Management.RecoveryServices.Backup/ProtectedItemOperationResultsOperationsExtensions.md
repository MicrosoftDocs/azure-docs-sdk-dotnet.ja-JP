<Type Name="ProtectedItemOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemOperationResultsOperationsExtensions = class" />
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
            <span data-ttu-id="e6d15-101">ProtectedItemOperationResultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e6d15-101">Extension methods for ProtectedItemOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemOperationResultsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, operationId As String) As ProtectedItemResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e6d15-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e6d15-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e6d15-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="e6d15-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e6d15-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="e6d15-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e6d15-105">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="e6d15-105">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e6d15-106">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="e6d15-106">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e6d15-107">バックアップ項目の名前詳細情報がフェッチされます。</span><span class="sxs-lookup"><span data-stu-id="e6d15-107">Backup item name whose details are to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="e6d15-108">その結果をフェッチする必要があります、操作を表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="e6d15-108">OperationID which represents the operation whose result needs to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e6d15-109">バックアップ項目に任意の操作の結果をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="e6d15-109">Fetches the result of any operation on the backup item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e6d15-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e6d15-110">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="e6d15-111">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="e6d15-111">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e6d15-112">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="e6d15-112">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="e6d15-113">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="e6d15-113">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="e6d15-114">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="e6d15-114">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="e6d15-115">バックアップ項目の名前詳細情報がフェッチされます。</span><span class="sxs-lookup"><span data-stu-id="e6d15-115">Backup item name whose details are to be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="e6d15-116">その結果をフェッチする必要があります、操作を表す OperationID です。</span><span class="sxs-lookup"><span data-stu-id="e6d15-116">OperationID which represents the operation whose result needs to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e6d15-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e6d15-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e6d15-118">バックアップ項目に任意の操作の結果をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="e6d15-118">Fetches the result of any operation on the backup item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>