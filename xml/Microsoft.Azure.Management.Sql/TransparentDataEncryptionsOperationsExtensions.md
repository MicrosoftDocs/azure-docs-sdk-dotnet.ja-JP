<Type Name="TransparentDataEncryptionsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransparentDataEncryptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransparentDataEncryptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransparentDataEncryptionsOperationsExtensions = class" />
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
            <span data-ttu-id="b1399-101">TransparentDataEncryptionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b1399-101">Extension methods for TransparentDataEncryptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption CreateOrUpdate (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption CreateOrUpdate(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITransparentDataEncryptionsOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As TransparentDataEncryption) As TransparentDataEncryption" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b1399-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b1399-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b1399-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b1399-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b1399-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b1399-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b1399-106">透過的なデータを設定すると、暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-106">The name of the database for which setting the transparent data encryption applies.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b1399-107">作成または更新の透過的なデータ暗号化の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b1399-107">The required parameters for creating or updating transparent data encryption.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1399-108">作成するか、データベースの透過的なデータ暗号化の構成を更新します。</span><span class="sxs-lookup"><span data-stu-id="b1399-108">Creates or updates a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b1399-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b1399-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b1399-110">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b1399-111">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b1399-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b1399-112">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b1399-113">透過的なデータを設定すると、暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-113">The name of the database for which setting the transparent data encryption applies.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b1399-114">作成または更新の透過的なデータ暗号化の必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b1399-114">The required parameters for creating or updating transparent data encryption.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b1399-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b1399-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1399-116">作成するか、データベースの透過的なデータ暗号化の構成を更新します。</span><span class="sxs-lookup"><span data-stu-id="b1399-116">Creates or updates a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption Get (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption Get(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITransparentDataEncryptionsOperations, resourceGroupName As String, serverName As String, databaseName As String) As TransparentDataEncryption" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b1399-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b1399-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b1399-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b1399-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b1399-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b1399-120">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b1399-121">透過的なデータ暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-121">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1399-122">データベースの透過的なデータ暗号化の構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="b1399-122">Gets a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; GetAsync (this Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; GetAsync(class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.TransparentDataEncryptionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b1399-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b1399-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b1399-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="b1399-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b1399-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="b1399-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="b1399-127">透過的なデータ暗号化が適用されるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="b1399-127">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b1399-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b1399-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b1399-129">データベースの透過的なデータ暗号化の構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="b1399-129">Gets a database's transparent data encryption configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>