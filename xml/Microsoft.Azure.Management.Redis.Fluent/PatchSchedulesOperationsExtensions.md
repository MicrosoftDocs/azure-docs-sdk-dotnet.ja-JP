<Type Name="PatchSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PatchSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PatchSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PatchSchedulesOperationsExtensions = class" />
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
            <span data-ttu-id="4613f-101">PatchSchedulesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4613f-101">Extension methods for PatchSchedulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; scheduleEntriesProperty, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; scheduleEntriesProperty, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, scheduleEntriesProperty, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scheduleEntriesProperty" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4613f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4613f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4613f-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-103">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4613f-104">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-104">The name of the Redis cache.</span></span>
            </param>
        <param name="scheduleEntriesProperty">
            <span data-ttu-id="4613f-105">Redis cache の修正プログラムのスケジュールの一覧です。</span><span class="sxs-lookup"><span data-stu-id="4613f-105">List of patch schedules for a Redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4613f-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4613f-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4613f-107">作成または Redis cache (Premium SKU が必要) の更新プログラムの適用スケジュールを置換します。</span><span class="sxs-lookup"><span data-stu-id="4613f-107">Create or replace the patching schedule for Redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4613f-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4613f-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4613f-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-109">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4613f-110">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-110">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4613f-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4613f-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4613f-112">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="4613f-112">Deletes the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; GetAsync (this Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt; GetAsync(class Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Redis.Fluent.PatchSchedulesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Redis.Fluent.Models.RedisPatchScheduleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Redis.Fluent.IPatchSchedulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4613f-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4613f-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4613f-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-114">The name of the resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4613f-115">Redis cache の名前。</span><span class="sxs-lookup"><span data-stu-id="4613f-115">The name of the redis cache.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4613f-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4613f-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4613f-117">(Premium SKU が必要) redis キャッシュの更新プログラムの適用スケジュールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4613f-117">Gets the patching schedule of a redis cache (requires Premium SKU).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>