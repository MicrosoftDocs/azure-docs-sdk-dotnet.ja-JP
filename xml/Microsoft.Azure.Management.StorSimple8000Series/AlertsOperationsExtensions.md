<Type Name="AlertsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AlertsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AlertsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AlertsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AlertsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="18502-101">AlertsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="18502-101">Extension methods for AlertsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public static void Clear (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Clear(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.Clear(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Clear (operations As IAlertsOperations, parameters As ClearAlertRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Clear : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.Clear (operations, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18502-103">アラートをクリア要求。</span><span class="sxs-lookup"><span data-stu-id="18502-103">The clear alert request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-105">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-106">アラートをオフにします。</span><span class="sxs-lookup"><span data-stu-id="18502-106">Clear the alerts.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ClearAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ClearAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, class Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ClearAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ClearAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ClearAsync (operations, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ClearAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ClearAlertRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-107">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18502-108">アラートをクリア要求。</span><span class="sxs-lookup"><span data-stu-id="18502-108">The clear alert request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-109">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-109">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-110">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-110">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="18502-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="18502-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-112">アラートをオフにします。</span><span class="sxs-lookup"><span data-stu-id="18502-112">Clear the alerts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IAlertsOperations, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of AlertFilter) = null) As IPage(Of Alert)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-114">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-114">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-115">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-115">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="18502-116">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="18502-116">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-117">マネージャー内のすべてのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="18502-117">Retrieves all the alerts in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ListByManagerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-119">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-119">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-120">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-120">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="18502-121">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="18502-121">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="18502-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="18502-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-123">マネージャー内のすべてのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="18502-123">Retrieves all the alerts in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManagerNext (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt; ListByManagerNext(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNext(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManagerNext (operations As IAlertsOperations, nextPageLink As String) As IPage(Of Alert)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNext : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-124">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="18502-125">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="18502-125">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-126">マネージャー内のすべてのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="18502-126">Retrieves all the alerts in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt; ListByManagerNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.ListByManagerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;ListByManagerNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Alert&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-127">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="18502-128">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="18502-128">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="18502-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="18502-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-130">マネージャー内のすべてのアラートを取得します。</span><span class="sxs-lookup"><span data-stu-id="18502-130">Retrieves all the alerts in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTestEmail">
      <MemberSignature Language="C#" Value="public static void SendTestEmail (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SendTestEmail(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmail(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub SendTestEmail (operations As IAlertsOperations, deviceName As String, parameters As SendTestAlertEmailRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member SendTestEmail : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmail (operations, deviceName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-131">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="18502-132">デバイス名</span><span class="sxs-lookup"><span data-stu-id="18502-132">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18502-133">送信は、アラートの電子メール要求をテストします。</span><span class="sxs-lookup"><span data-stu-id="18502-133">The send test alert email request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-134">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-134">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-135">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-135">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-136">テスト アラートの電子メールを送信します。</span><span class="sxs-lookup"><span data-stu-id="18502-136">Sends a test alert email.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTestEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task SendTestEmailAsync (this Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task SendTestEmailAsync(class Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations operations, string deviceName, class Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmailAsync(Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SendTestEmailAsync : Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations * string * Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions.SendTestEmailAsync (operations, deviceName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.AlertsOperationsExtensions/&lt;SendTestEmailAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IAlertsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18502-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="18502-137">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="18502-138">デバイス名</span><span class="sxs-lookup"><span data-stu-id="18502-138">The device name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18502-139">送信は、アラートの電子メール要求をテストします。</span><span class="sxs-lookup"><span data-stu-id="18502-139">The send test alert email request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18502-140">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="18502-140">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="18502-141">管理者名</span><span class="sxs-lookup"><span data-stu-id="18502-141">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="18502-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="18502-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18502-143">テスト アラートの電子メールを送信します。</span><span class="sxs-lookup"><span data-stu-id="18502-143">Sends a test alert email.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>