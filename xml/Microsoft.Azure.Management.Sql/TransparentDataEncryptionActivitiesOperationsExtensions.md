<Type Name="TransparentDataEncryptionActivitiesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransparentDataEncryptionActivitiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransparentDataEncryptionActivitiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransparentDataEncryptionActivitiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionActivitiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b8219-101">TransparentDataEncryptionActivitiesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b8219-101">Extension methods for TransparentDataEncryptionActivitiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByConfiguration">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt; ListByConfiguration (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt; ListByConfiguration(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions.ListByConfiguration(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByConfiguration (operations As ITransparentDataEncryptionActivitiesOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of TransparentDataEncryptionActivity)" />
      <MemberSignature Language="F#" Value="static member ListByConfiguration : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions.ListByConfiguration (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8219-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b8219-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8219-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b8219-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b8219-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b8219-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b8219-106">透過的なデータ暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-106">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8219-107">データベースの透過的なデータ暗号化操作の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="b8219-107">Returns a database's transparent data encryption operation result.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByConfigurationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt; ListByConfigurationAsync (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt; ListByConfigurationAsync(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions.ListByConfigurationAsync(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByConfigurationAsync : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions.ListByConfigurationAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.TransparentDataEncryptionActivitiesOperationsExtensions/&lt;ListByConfigurationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b8219-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b8219-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b8219-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b8219-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b8219-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b8219-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-111">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b8219-112">透過的なデータ暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b8219-112">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b8219-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b8219-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b8219-114">データベースの透過的なデータ暗号化操作の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="b8219-114">Returns a database's transparent data encryption operation result.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>