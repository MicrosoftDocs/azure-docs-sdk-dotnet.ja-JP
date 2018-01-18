<Type Name="RedisOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.RedisOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RedisOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RedisOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.RedisOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RedisOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RedisOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="687f5-101">RedisOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="687f5-101">Extension methods for RedisOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisResource BeginCreate (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisResource BeginCreate(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As RedisCreateParameters) As RedisResource" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginCreate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-103">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-104">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-104">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-105">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-105">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-106">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="687f5-106">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; BeginCreateAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; BeginCreateAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;BeginCreateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-108">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-109">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-109">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-110">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-110">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-112">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="687f5-112">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRedisOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Redis.IRedisOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginDelete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-114">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-115">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-115">The name of the Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-116">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="687f5-116">Deletes a Redis cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;BeginDeleteAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-119">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-119">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-121">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="687f5-121">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExportData">
      <MemberSignature Language="C#" Value="public static void BeginExportData (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginExportData(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginExportData(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginExportData (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As ExportRDBParameters)" />
      <MemberSignature Language="F#" Value="static member BeginExportData : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginExportData (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-123">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-124">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-124">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-125">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-125">Parameters for Redis export operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-126">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-126">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginExportDataAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginExportDataAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginExportDataAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExportDataAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;BeginExportDataAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-128">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-129">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-129">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-130">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-130">Parameters for Redis export operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-132">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-132">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImportData">
      <MemberSignature Language="C#" Value="public static void BeginImportData (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginImportData(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginImportData(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginImportData (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As ImportRDBParameters)" />
      <MemberSignature Language="F#" Value="static member BeginImportData : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginImportData (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-134">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-135">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-135">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-136">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-136">Parameters for Redis import operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-137">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-137">Import data into Redis cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginImportDataAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginImportDataAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginImportDataAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginImportDataAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.BeginImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;BeginImportDataAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-139">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-140">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-140">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-141">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-141">Parameters for Redis import operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-143">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-143">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisResource Create (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisResource Create(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Create(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As RedisCreateParameters) As RedisResource" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Create (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-145">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-146">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-146">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-147">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-147">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-148">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="687f5-148">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; CreateAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; CreateAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.CreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-150">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-151">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-151">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-152">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-152">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-154">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="687f5-154">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Delete(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRedisOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Redis.IRedisOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-156">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-157">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-157">The name of the Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-158">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="687f5-158">Deletes a Redis cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-160">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-160">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-161">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-161">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-163">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="687f5-163">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportData">
      <MemberSignature Language="C#" Value="public static void ExportData (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ExportData(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ExportData(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ExportData (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As ExportRDBParameters)" />
      <MemberSignature Language="F#" Value="static member ExportData : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ExportData (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-165">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-166">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-166">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-167">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-167">Parameters for Redis export operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-168">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-168">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExportDataAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExportDataAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ExportRDBParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ExportDataAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ExportRDBParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportDataAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ExportRDBParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ExportDataAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-170">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-170">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-171">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-171">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-172">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-172">Parameters for Redis export operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-174">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-174">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceReboot">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse ForceReboot (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse ForceReboot(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ForceReboot(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRebootParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ForceReboot (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As RedisRebootParameters) As RedisForceRebootResponse" />
      <MemberSignature Language="F#" Value="static member ForceReboot : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisRebootParameters -&gt; Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ForceReboot (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-176">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-176">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-177">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-177">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-178">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-178">Specifies which Redis node(s) to reboot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-179">指定した Redis ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="687f5-179">Reboot specified Redis node(s).</span></span> <span data-ttu-id="687f5-180">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-180">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="687f5-181">データ損失の可能性があります。</span><span class="sxs-lookup"><span data-stu-id="687f5-181">There can be potential data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt; ForceRebootAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt; ForceRebootAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRebootParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ForceRebootAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRebootParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForceRebootAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisRebootParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ForceRebootAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ForceRebootAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisForceRebootResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRebootParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-183">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-184">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-184">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-185">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-185">Specifies which Redis node(s) to reboot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-187">指定した Redis ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="687f5-187">Reboot specified Redis node(s).</span></span> <span data-ttu-id="687f5-188">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-188">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="687f5-189">データ損失の可能性があります。</span><span class="sxs-lookup"><span data-stu-id="687f5-189">There can be potential data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisResource Get (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisResource Get(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Get(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRedisOperations, resourceGroupName As String, name As String) As RedisResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Redis.IRedisOperations * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-191">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-192">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-192">The name of the Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-193">Redis cache (リソースの説明) を取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-193">Gets a Redis cache (resource description).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; GetAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; GetAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-195">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-195">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-196">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-196">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-198">Redis cache (リソースの説明) を取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-198">Gets a Redis cache (resource description).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportData">
      <MemberSignature Language="C#" Value="public static void ImportData (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ImportData(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ImportData(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ImportData (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As ImportRDBParameters)" />
      <MemberSignature Language="F#" Value="static member ImportData : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters -&gt; unit" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ImportData (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-200">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-200">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-201">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-201">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-202">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-202">Parameters for Redis import operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-203">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-203">Import data into Redis cache.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ImportDataAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ImportDataAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.ImportRDBParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ImportDataAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.ImportRDBParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportDataAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.ImportRDBParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ImportDataAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-205">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-205">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-206">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-206">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-207">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="687f5-207">Parameters for Redis import operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-209">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="687f5-209">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; List (this Microsoft.Azure.Management.Redis.IRedisOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; List(class Microsoft.Azure.Management.Redis.IRedisOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.List(Microsoft.Azure.Management.Redis.IRedisOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRedisOperations) As IPage(Of RedisResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Redis.IRedisOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-210">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-211">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-211">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Redis.IRedisOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-212">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-214">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-214">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Redis.IRedisOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IRedisOperations, resourceGroupName As String) As IPage(Of RedisResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Redis.IRedisOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-216">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-217">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="687f5-217">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-219">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-219">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-221">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="687f5-221">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Redis.IRedisOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IRedisOperations, nextPageLink As String) As IPage(Of RedisResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Redis.IRedisOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-222">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="687f5-223">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="687f5-223">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-224">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="687f5-224">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-225">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="687f5-226">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="687f5-226">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-228">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="687f5-228">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisAccessKeys ListKeys (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys ListKeys(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListKeys(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IRedisOperations, resourceGroupName As String, name As String) As RedisAccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.Redis.IRedisOperations * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListKeys (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-230">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-230">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-231">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-231">The name of the Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-232">Redis cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-232">Retrieve a Redis cache's access keys.</span></span> <span data-ttu-id="687f5-233">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-233">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListKeysAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ListKeysAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-235">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-235">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-236">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-236">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-238">Redis cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-238">Retrieve a Redis cache's access keys.</span></span> <span data-ttu-id="687f5-239">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-239">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListNext (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; ListNext(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListNext(Microsoft.Azure.Management.Redis.IRedisOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRedisOperations, nextPageLink As String) As IPage(Of RedisResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Redis.IRedisOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="687f5-241">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="687f5-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-242">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-242">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;ListNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="687f5-244">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="687f5-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-246">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="687f5-246">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisAccessKeys RegenerateKey (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys RegenerateKey(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As RedisRegenerateKeyParameters) As RedisAccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters -&gt; Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.RegenerateKey (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-248">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-249">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-249">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-250">再生成するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-250">Specifies which key to regenerate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-251">Redis cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="687f5-251">Regenerate Redis cache's access keys.</span></span> <span data-ttu-id="687f5-252">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-252">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisRegenerateKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-253">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-253">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-254">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-254">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-255">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-255">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-256">再生成するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="687f5-256">Specifies which key to regenerate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-257">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-258">Redis cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="687f5-258">Regenerate Redis cache's access keys.</span></span> <span data-ttu-id="687f5-259">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="687f5-259">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisResource Update (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisResource Update(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Update(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRedisOperations, resourceGroupName As String, name As String, parameters As RedisUpdateParameters) As RedisResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.Update (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-260">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-261">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-261">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-262">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-262">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-263">更新プログラムの Redis 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="687f5-263">Parameters supplied to the Update Redis operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-264">既存の Redis キャッシュを更新します。</span><span class="sxs-lookup"><span data-stu-id="687f5-264">Update an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt; UpdateAsync (this Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisResource&gt; UpdateAsync(class Microsoft.Azure.Management.Redis.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.RedisOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Redis.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Redis.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;" Usage="Microsoft.Azure.Management.Redis.RedisOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.RedisOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="687f5-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="687f5-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="687f5-266">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-266">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="687f5-267">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="687f5-267">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="687f5-268">更新プログラムの Redis 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="687f5-268">Parameters supplied to the Update Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="687f5-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="687f5-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="687f5-270">既存の Redis キャッシュを更新します。</span><span class="sxs-lookup"><span data-stu-id="687f5-270">Update an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>