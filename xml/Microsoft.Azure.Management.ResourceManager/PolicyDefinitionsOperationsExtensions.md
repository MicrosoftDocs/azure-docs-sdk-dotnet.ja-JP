<Type Name="PolicyDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PolicyDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PolicyDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PolicyDefinitionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5399c-101">PolicyDefinitionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5399c-101">Extension methods for PolicyDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPolicyDefinitionsOperations, policyDefinitionName As String, parameters As PolicyDefinition) As PolicyDefinition" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdate (operations, policyDefinitionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-103">作成するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-103">The name of the policy definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5399c-104">ポリシー定義のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="5399c-104">The policy definition properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-105">作成するか、ポリシーの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="5399c-105">Creates or updates a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.CreateOrUpdateAsync (operations, policyDefinitionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-106">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-107">作成するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-107">The name of the policy definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5399c-108">ポリシー定義のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="5399c-108">The policy definition properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5399c-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5399c-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-110">作成するか、ポリシーの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="5399c-110">Creates or updates a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPolicyDefinitionsOperations, policyDefinitionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Delete (operations, policyDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-111">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-112">削除するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-112">The name of the policy definition to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-113">ポリシーの定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="5399c-113">Deletes a policy definition.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.DeleteAsync (operations, policyDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-114">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-115">削除するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-115">The name of the policy definition to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5399c-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5399c-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-117">ポリシーの定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="5399c-117">Deletes a policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition Get (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition Get(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPolicyDefinitionsOperations, policyDefinitionName As String) As PolicyDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.Get (operations, policyDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-118">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-119">取得するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-119">The name of the policy definition to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-120">ポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-120">Gets the policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string policyDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.GetAsync (operations, policyDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="policyDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-121">The operations group for this extension method.</span></span>
            </param>
        <param name="policyDefinitionName">
            <span data-ttu-id="5399c-122">取得するポリシーの定義の名前。</span><span class="sxs-lookup"><span data-stu-id="5399c-122">The name of the policy definition to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5399c-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5399c-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-124">ポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-124">Gets the policy definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPolicyDefinitionsOperations, Optional odataQuery As ODataQuery(Of PolicyDefinition) = null) As IPage(Of PolicyDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-125">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5399c-126">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5399c-126">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-127">サブスクリプションのすべてのポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-127">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-128">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5399c-129">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5399c-129">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5399c-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5399c-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-131">サブスクリプションのすべてのポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-131">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPolicyDefinitionsOperations, nextPageLink As String) As IPage(Of PolicyDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-132">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5399c-133">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5399c-133">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-134">サブスクリプションのすべてのポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-134">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicyDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicyDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5399c-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5399c-135">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5399c-136">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5399c-136">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5399c-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5399c-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5399c-138">サブスクリプションのすべてのポリシー定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="5399c-138">Gets all the policy definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>