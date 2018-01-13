<Type Name="RedisOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RedisOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RedisOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RedisOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RedisOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="097c5-101">RedisOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="097c5-101">Extension methods for RedisOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-103">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-104">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-104">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-105">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="097c5-105">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-107">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="097c5-107">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-109">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-110">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-110">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-112">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="097c5-112">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginExportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginExportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginExportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginExportDataAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-114">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-115">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-115">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-116">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="097c5-116">Parameters for Redis export operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-118">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="097c5-118">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginImportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginImportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginImportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginImportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.BeginImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;BeginImportDataAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-120">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-121">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-121">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-122">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="097c5-122">Parameters for Redis import operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-124">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="097c5-124">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; CreateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; CreateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.CreateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-126">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-126">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-127">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-127">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-128">パラメーターは、Redis 作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="097c5-128">Parameters supplied to the Create Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-130">作成または既存の Redis cache (上書き/再作成して、潜在的なダウンタイムで) を置換します。</span><span class="sxs-lookup"><span data-stu-id="097c5-130">Create or replace (overwrite/recreate, with potential downtime) an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-132">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-133">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-133">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-135">Redis キャッシュを削除します。</span><span class="sxs-lookup"><span data-stu-id="097c5-135">Deletes a Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ExportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ExportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ExportDataAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-137">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-137">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-138">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-138">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-139">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="097c5-139">Parameters for Redis export operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-141">Redis cache のデータをコンテナー内の blob にエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="097c5-141">Export data from the redis cache to blobs in a container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt; ForceRebootAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt; ForceRebootAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ForceRebootAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForceRebootAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ForceRebootAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ForceRebootAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisForceRebootResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisRebootParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-143">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-144">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-144">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-145">ノードを再起動する Redis を指定します。</span><span class="sxs-lookup"><span data-stu-id="097c5-145">Specifies which Redis node(s) to reboot.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-147">指定した Redis ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="097c5-147">Reboot specified Redis node(s).</span></span> <span data-ttu-id="097c5-148">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="097c5-148">This operation requires write permission to the cache resource.</span></span> <span data-ttu-id="097c5-149">データ損失の可能性があります。</span><span class="sxs-lookup"><span data-stu-id="097c5-149">There can be potential data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; GetAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; GetAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-151">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-152">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-152">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-154">Redis cache (リソースの説明) を取得します。</span><span class="sxs-lookup"><span data-stu-id="097c5-154">Gets a Redis cache (resource description).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDataAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ImportDataAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ImportDataAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ImportDataAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportDataAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ImportDataAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ImportDataAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-156">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-157">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-157">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-158">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="097c5-158">Parameters for Redis import operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-160">Redis キャッシュにデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="097c5-160">Import data into Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-161">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-163">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="097c5-163">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-165">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-167">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="097c5-167">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-168">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="097c5-169">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="097c5-169">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-171">リソース グループ内のすべての Redis キャッシュの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="097c5-171">Lists all Redis caches in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListKeysAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListKeysAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-173">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-174">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-174">The name of the Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-176">Redis cache のアクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="097c5-176">Retrieve a Redis cache's access keys.</span></span> <span data-ttu-id="097c5-177">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="097c5-177">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;ListNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-178">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="097c5-179">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="097c5-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-181">指定されたサブスクリプション内のすべての Redis キャッシュを取得します。</span><span class="sxs-lookup"><span data-stu-id="097c5-181">Gets all Redis caches in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, valuetype Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType keyType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, name, keyType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisAccessKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisKeyType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-183">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-184">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-184">The name of the Redis cache.</span></span>
            </param>
        <param name="keyType">
            <span data-ttu-id="097c5-185">Redis アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="097c5-185">The Redis access key to regenerate.</span></span> <span data-ttu-id="097c5-186">使用可能な値が含まれます 'Primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="097c5-186">Possible values include: 'Primary', 'Secondary'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-188">Redis cache のアクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="097c5-188">Regenerate Redis cache's access keys.</span></span> <span data-ttu-id="097c5-189">この操作には、キャッシュのリソースに対する書き込み権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="097c5-189">This operation requires write permission to the cache resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; UpdateAsync (this Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt; UpdateAsync(class Microsoft.Azure.Management.Redis.Fluent.IRedisOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Redis.Fluent.IRedisOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Redis.Fluent.IRedisOperations * string * string * Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.RedisOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IRedisOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Fluent.Models.RedisUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="097c5-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="097c5-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="097c5-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-191">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="097c5-192">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="097c5-192">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="097c5-193">更新プログラムの Redis 操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="097c5-193">Parameters supplied to the Update Redis operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="097c5-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="097c5-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="097c5-195">既存の Redis キャッシュを更新します。</span><span class="sxs-lookup"><span data-stu-id="097c5-195">Update an existing Redis cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>