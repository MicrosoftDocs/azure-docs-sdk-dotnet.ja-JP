<Type Name="ContainerLogsOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerLogsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerLogsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerLogsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerLogsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17e42-101">ContainerLogsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="17e42-101">Extension methods for ContainerLogsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerInstance.Models.Logs List (this Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerInstance.Models.Logs List(class Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.List(Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerLogsOperations, resourceGroupName As String, containerGroupName As String, containerName As String, Optional tail As Nullable(Of Integer) = null) As Logs" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.Logs" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.List (operations, resourceGroupName, containerGroupName, containerName, tail)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.Logs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="17e42-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="17e42-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="17e42-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-103">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="17e42-104">コンテナーのグループの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-104">The name of the container group.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="17e42-105">コンテナーのインスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-105">The name of the container instance.</span></span>
            </param>
        <param name="tail">
            <span data-ttu-id="17e42-106">コンテナーのインスタンスのログの末尾が示される行の数。</span><span class="sxs-lookup"><span data-stu-id="17e42-106">The number of lines to show from the tail of the container instance log.</span></span> <span data-ttu-id="17e42-107">指定しない場合、使用可能なすべてのログは、最大 4 mb のとおりです。</span><span class="sxs-lookup"><span data-stu-id="17e42-107">If not provided, all available logs are shown up to 4mb.</span></span>
            </param>
        <summary>
            <span data-ttu-id="17e42-108">インスタンスの指定されたコンテナーのログを取得します。</span><span class="sxs-lookup"><span data-stu-id="17e42-108">Get the logs for a specified container instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="17e42-109">ログは、指定されたリソース グループおよびコンテナーのグループで指定されたコンテナー インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="17e42-109">Get the logs for a specified container instance in a specified resource group and container group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt; ListAsync (this Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt; ListAsync(class Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations operations, string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;" Usage="Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions.ListAsync (operations, resourceGroupName, containerGroupName, containerName, tail, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerInstance.ContainerLogsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="17e42-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="17e42-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="17e42-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-111">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="17e42-112">コンテナーのグループの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-112">The name of the container group.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="17e42-113">コンテナーのインスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="17e42-113">The name of the container instance.</span></span>
            </param>
        <param name="tail">
            <span data-ttu-id="17e42-114">コンテナーのインスタンスのログの末尾が示される行の数。</span><span class="sxs-lookup"><span data-stu-id="17e42-114">The number of lines to show from the tail of the container instance log.</span></span> <span data-ttu-id="17e42-115">指定しない場合、使用可能なすべてのログは、最大 4 mb のとおりです。</span><span class="sxs-lookup"><span data-stu-id="17e42-115">If not provided, all available logs are shown up to 4mb.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="17e42-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="17e42-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="17e42-117">インスタンスの指定されたコンテナーのログを取得します。</span><span class="sxs-lookup"><span data-stu-id="17e42-117">Get the logs for a specified container instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="17e42-118">ログは、指定されたリソース グループおよびコンテナーのグループで指定されたコンテナー インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="17e42-118">Get the logs for a specified container instance in a specified resource group and container group.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>