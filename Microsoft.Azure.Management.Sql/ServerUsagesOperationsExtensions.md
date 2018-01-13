<Type Name="ServerUsagesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerUsagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerUsagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerUsagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerUsagesOperationsExtensions = class" />
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
            <span data-ttu-id="b0a3e-101">ServerUsagesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-101">Extension methods for ServerUsagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt; ListByServer (this Microsoft.Azure.Management.Sql.IServerUsagesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerUsage&gt; ListByServer(class Microsoft.Azure.Management.Sql.IServerUsagesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IServerUsagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IServerUsagesOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of ServerUsage)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IServerUsagesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;" Usage="Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b0a3e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b0a3e-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b0a3e-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b0a3e-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-105">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0a3e-106">サーバーの使用法を返します。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-106">Returns server usages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IServerUsagesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IServerUsagesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IServerUsagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IServerUsagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerUsagesOperationsExtensions/&lt;ListByServerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b0a3e-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b0a3e-108">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-108">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b0a3e-109">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-109">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b0a3e-110">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-110">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0a3e-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0a3e-112">サーバーの使用法を返します。</span><span class="sxs-lookup"><span data-stu-id="b0a3e-112">Returns server usages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>