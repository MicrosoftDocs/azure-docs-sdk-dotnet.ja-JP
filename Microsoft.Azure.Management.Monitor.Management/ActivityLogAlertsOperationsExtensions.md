<Type Name="ActivityLogAlertsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityLogAlertsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityLogAlertsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityLogAlertsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="43f19-101">ActivityLogAlertsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="43f19-101">Extension methods for ActivityLogAlertsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource CreateOrUpdate (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource activityLogAlert);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource CreateOrUpdate(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource activityLogAlert) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IActivityLogAlertsOperations, resourceGroupName As String, activityLogAlertName As String, activityLogAlert As ActivityLogAlertResource) As ActivityLogAlertResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, activityLogAlertName, activityLogAlert)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="activityLogAlert" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-103">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-104">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-104">The name of the activity log alert.</span></span>
            </param>
        <param name="activityLogAlert">
            <span data-ttu-id="43f19-105">作成または更新に使用するアクティビティのログのアラート。</span><span class="sxs-lookup"><span data-stu-id="43f19-105">The activity log alert to create or use for the update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-106">新しいアクティビティのログのアラートを生成または既存のものを更新します。</span><span class="sxs-lookup"><span data-stu-id="43f19-106">Create a new activity log alert or update an existing one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource activityLogAlert, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource activityLogAlert, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, activityLogAlertName, activityLogAlert, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="activityLogAlert" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-108">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-109">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-109">The name of the activity log alert.</span></span>
            </param>
        <param name="activityLogAlert">
            <span data-ttu-id="43f19-110">作成または更新に使用するアクティビティのログのアラート。</span><span class="sxs-lookup"><span data-stu-id="43f19-110">The activity log alert to create or use for the update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-112">新しいアクティビティのログのアラートを生成または既存のものを更新します。</span><span class="sxs-lookup"><span data-stu-id="43f19-112">Create a new activity log alert or update an existing one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Delete(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IActivityLogAlertsOperations, resourceGroupName As String, activityLogAlertName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Delete (operations, resourceGroupName, activityLogAlertName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-114">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-115">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-115">The name of the activity log alert.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-116">アクティビティのログのアラートを削除します。</span><span class="sxs-lookup"><span data-stu-id="43f19-116">Delete an activity log alert.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.DeleteAsync (operations, resourceGroupName, activityLogAlertName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-118">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-119">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-119">The name of the activity log alert.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-121">アクティビティのログのアラートを削除します。</span><span class="sxs-lookup"><span data-stu-id="43f19-121">Delete an activity log alert.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource Get (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource Get(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IActivityLogAlertsOperations, resourceGroupName As String, activityLogAlertName As String) As ActivityLogAlertResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Get (operations, resourceGroupName, activityLogAlertName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-123">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-124">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-124">The name of the activity log alert.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-125">アクティビティのログのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-125">Get an activity log alert.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.GetAsync (operations, resourceGroupName, activityLogAlertName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-127">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-128">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-128">The name of the activity log alert.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-130">アクティビティのログのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-130">Get an activity log alert.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IActivityLogAlertsOperations, resourceGroupName As String) As IEnumerable(Of ActivityLogAlertResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-132">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-133">リソース グループ内のすべてのアクティビティの一覧のログのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-133">Get a list of all activity log alerts in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-135">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-137">リソース グループ内のすべてのアクティビティの一覧のログのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-137">Get a list of all activity log alerts in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionId">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; ListBySubscriptionId (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; ListBySubscriptionId(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListBySubscriptionId(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionId (operations As IActivityLogAlertsOperations) As IEnumerable(Of ActivityLogAlertResource)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionId : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListBySubscriptionId operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-138">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-139">サブスクリプション ログ アラートすべてのアクティビティの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-139">Get a list of all activity log alerts in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt; ListBySubscriptionIdAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt; ListBySubscriptionIdAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListBySubscriptionIdAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionIdAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.ListBySubscriptionIdAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;ListBySubscriptionIdAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-140">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-142">サブスクリプション ログ アラートすべてのアクティビティの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="43f19-142">Get a list of all activity log alerts in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource Update (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody activityLogAlertPatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource Update(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody activityLogAlertPatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Update(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IActivityLogAlertsOperations, resourceGroupName As String, activityLogAlertName As String, activityLogAlertPatch As ActivityLogAlertPatchBody) As ActivityLogAlertResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.Update (operations, resourceGroupName, activityLogAlertName, activityLogAlertPatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="activityLogAlertPatch" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-144">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-145">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-145">The name of the activity log alert.</span></span>
            </param>
        <param name="activityLogAlertPatch">
            <span data-ttu-id="43f19-146">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="43f19-146">Parameters supplied to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-147">既存の ActivityLogAlertResource のタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="43f19-147">Updates an existing ActivityLogAlertResource's tags.</span></span> <span data-ttu-id="43f19-148">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="43f19-148">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; UpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody activityLogAlertPatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt; UpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations operations, string resourceGroupName, string activityLogAlertName, class Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody activityLogAlertPatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions.UpdateAsync (operations, resourceGroupName, activityLogAlertName, activityLogAlertPatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActivityLogAlertsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="activityLogAlertName" Type="System.String" />
        <Parameter Name="activityLogAlertPatch" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertPatchBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="43f19-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="43f19-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="43f19-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-150">The name of the resource group.</span></span>
            </param>
        <param name="activityLogAlertName">
            <span data-ttu-id="43f19-151">アクティビティのログのアラートの名前。</span><span class="sxs-lookup"><span data-stu-id="43f19-151">The name of the activity log alert.</span></span>
            </param>
        <param name="activityLogAlertPatch">
            <span data-ttu-id="43f19-152">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="43f19-152">Parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="43f19-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="43f19-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="43f19-154">既存の ActivityLogAlertResource のタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="43f19-154">Updates an existing ActivityLogAlertResource's tags.</span></span> <span data-ttu-id="43f19-155">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="43f19-155">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>