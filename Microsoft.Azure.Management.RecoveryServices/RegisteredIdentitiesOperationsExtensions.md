<Type Name="RegisteredIdentitiesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RegisteredIdentitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RegisteredIdentitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RegisteredIdentitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RegisteredIdentitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1dee9-101">RegisteredIdentitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1dee9-101">Extension methods for RegisteredIdentitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations operations, string resourceGroupName, string vaultName, string identityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations operations, string resourceGroupName, string vaultName, string identityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRegisteredIdentitiesOperations, resourceGroupName As String, vaultName As String, identityName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions.Delete (operations, resourceGroupName, vaultName, identityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="identityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dee9-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dee9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dee9-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="1dee9-104">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1dee9-104">The name of the recovery services vault.</span></span>
            </param>
        <param name="identityName">
            <span data-ttu-id="1dee9-105">コンテナーの名前、保護の登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-105">Name of the protection container to unregister.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dee9-106">Recovery Services コンテナーから、指定したコンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-106">Unregisters the given container from your Recovery Services vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations operations, string resourceGroupName, string vaultName, string identityName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations operations, string resourceGroupName, string vaultName, string identityName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, identityName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.RegisteredIdentitiesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IRegisteredIdentitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="identityName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1dee9-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1dee9-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1dee9-108">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="1dee9-109">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="1dee9-109">The name of the recovery services vault.</span></span>
            </param>
        <param name="identityName">
            <span data-ttu-id="1dee9-110">コンテナーの名前、保護の登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-110">Name of the protection container to unregister.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1dee9-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1dee9-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1dee9-112">Recovery Services コンテナーから、指定したコンテナーの登録を解除します。</span><span class="sxs-lookup"><span data-stu-id="1dee9-112">Unregisters the given container from your Recovery Services vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>