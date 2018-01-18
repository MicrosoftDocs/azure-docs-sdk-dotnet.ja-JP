<Type Name="PatchSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PatchSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PatchSchedulesOperationsExtensions = class" />
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
            <span data-ttu-id="de48f-101">PatchSchedulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="de48f-101">Extension methods for PatchSchedulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule CreateOrUpdate (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule CreateOrUpdate(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String, parameters As RedisPatchSchedule) As RedisPatchSchedule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule -&gt; Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-103">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-104">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-104">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de48f-105">Redis cache の更新プログラムの適用スケジュールを設定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de48f-105">Parameters to set the patching schedule for Redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-106">作成または Redis cache (Premium SKU が必要) の更新プログラムの適用スケジュールを置換します。</span><span class="sxs-lookup"><span data-stu-id="de48f-106">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-108">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-109">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-109">The name of the Redis cache.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="de48f-110">Redis cache の更新プログラムの適用スケジュールを設定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="de48f-110">Parameters to set the patching schedule for Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de48f-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de48f-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-112">作成または Redis cache (Premium SKU が必要) の更新プログラムの適用スケジュールを置換します。</span><span class="sxs-lookup"><span data-stu-id="de48f-112">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Delete(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-114">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-115">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-115">The name of the redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-116">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="de48f-116">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-118">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-119">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-119">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de48f-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de48f-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-121">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="de48f-121">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule Get (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule Get(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Get(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPatchSchedulesOperations, resourceGroupName As String, name As String) As RedisPatchSchedule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string -&gt; Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-123">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-124">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-124">The name of the redis cache.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-125">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="de48f-125">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; GetAsync (this Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt; GetAsync(class Microsoft.Azure.Management.Redis.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;" Usage="Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.PatchSchedulesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Models.RedisPatchSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="de48f-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="de48f-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="de48f-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-127">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="de48f-128">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="de48f-128">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="de48f-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="de48f-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="de48f-130">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="de48f-130">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>