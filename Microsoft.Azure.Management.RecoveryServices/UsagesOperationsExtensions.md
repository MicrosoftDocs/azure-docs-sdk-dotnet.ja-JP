<Type Name="UsagesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsagesOperationsExtensions = class" />
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
            <span data-ttu-id="7ff45-101">UsagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7ff45-101">Extension methods for UsagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByVaults">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt; ListByVaults (this Microsoft.Azure.Management.RecoveryServices.IUsagesOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt; ListByVaults(class Microsoft.Azure.Management.RecoveryServices.IUsagesOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions.ListByVaults(Microsoft.Azure.Management.RecoveryServices.IUsagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByVaults (operations As IUsagesOperations, resourceGroupName As String, vaultName As String) As IEnumerable(Of VaultUsage)" />
      <MemberSignature Language="F#" Value="static member ListByVaults : Microsoft.Azure.Management.RecoveryServices.IUsagesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions.ListByVaults (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ff45-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ff45-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ff45-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7ff45-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7ff45-104">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ff45-104">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ff45-105">資格情報コンテナーの使用状況をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="7ff45-105">Fetches the usages of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByVaultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;&gt; ListByVaultsAsync (this Microsoft.Azure.Management.RecoveryServices.IUsagesOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;&gt; ListByVaultsAsync(class Microsoft.Azure.Management.RecoveryServices.IUsagesOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions.ListByVaultsAsync(Microsoft.Azure.Management.RecoveryServices.IUsagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByVaultsAsync : Microsoft.Azure.Management.RecoveryServices.IUsagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions.ListByVaultsAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.UsagesOperationsExtensions/&lt;ListByVaultsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ff45-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ff45-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ff45-107">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="7ff45-107">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="7ff45-108">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="7ff45-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ff45-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ff45-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ff45-110">資格情報コンテナーの使用状況をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="7ff45-110">Fetches the usages of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>