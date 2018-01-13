<Type Name="AlertRuleIncidentsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AlertRuleIncidentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AlertRuleIncidentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AlertRuleIncidentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AlertRuleIncidentsOperationsExtensions = class" />
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
            <span data-ttu-id="c1859-101">AlertRuleIncidentsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c1859-101">Extension methods for AlertRuleIncidentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.Incident Get (this Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, string incidentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.Incident Get(class Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, string incidentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAlertRuleIncidentsOperations, resourceGroupName As String, ruleName As String, incidentName As String) As Incident" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations * string * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.Incident" Usage="Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.Get (operations, resourceGroupName, ruleName, incidentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.Incident</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="incidentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1859-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c1859-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1859-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-103">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="c1859-104">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-104">The name of the rule.</span></span>
            </param>
        <param name="incidentName">
            <span data-ttu-id="c1859-105">取得するためにインシデントの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-105">The name of the incident to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1859-106">アラート ルールに関連付けられているインシデントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c1859-106">Gets an incident associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, string incidentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, string incidentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.GetAsync (operations, resourceGroupName, ruleName, incidentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="incidentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1859-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c1859-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1859-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-108">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="c1859-109">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-109">The name of the rule.</span></span>
            </param>
        <param name="incidentName">
            <span data-ttu-id="c1859-110">取得するためにインシデントの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-110">The name of the incident to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1859-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c1859-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1859-112">アラート ルールに関連付けられているインシデントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c1859-112">Gets an incident associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAlertRule">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt; ListByAlertRule (this Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt; ListByAlertRule(class Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.ListByAlertRule(Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAlertRule (operations As IAlertRuleIncidentsOperations, resourceGroupName As String, ruleName As String) As IEnumerable(Of Incident)" />
      <MemberSignature Language="F#" Value="static member ListByAlertRule : Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.ListByAlertRule (operations, resourceGroupName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1859-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c1859-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1859-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-114">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="c1859-115">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-115">The name of the rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1859-116">アラート ルールに関連付けられているインシデントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1859-116">Gets a list of incidents associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAlertRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt; ListByAlertRuleAsync (this Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt; ListByAlertRuleAsync(class Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations operations, string resourceGroupName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.ListByAlertRuleAsync(Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAlertRuleAsync : Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions.ListByAlertRuleAsync (operations, resourceGroupName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.AlertRuleIncidentsOperationsExtensions/&lt;ListByAlertRuleAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1859-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c1859-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1859-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-118">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="c1859-119">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="c1859-119">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c1859-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c1859-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1859-121">アラート ルールに関連付けられているインシデントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1859-121">Gets a list of incidents associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>