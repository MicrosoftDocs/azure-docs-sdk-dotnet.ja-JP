<Type Name="PolicySetDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PolicySetDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PolicySetDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PolicySetDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PolicySetDefinitionsOperationsExtensions = class" />
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
            <span data-ttu-id="a3561-101">PolicySetDefinitionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a3561-101">Extension methods for PolicySetDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPolicySetDefinitionsOperations, policySetDefinitionName As String, parameters As PolicySetDefinition) As PolicySetDefinition" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.CreateOrUpdate (operations, policySetDefinitionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-102">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-103">ポリシーの名前は、作成する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-103">The name of the policy set definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a3561-104">ポリシーは、定義のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-104">The policy set definition properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-105">作成するか、ポリシーのセットの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="a3561-105">Creates or updates a policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.CreateOrUpdateAsync (operations, policySetDefinitionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-106">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-107">ポリシーの名前は、作成する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-107">The name of the policy set definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a3561-108">ポリシーは、定義のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-108">The policy set definition properties.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3561-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3561-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-110">作成するか、ポリシーのセットの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="a3561-110">Creates or updates a policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IPolicySetDefinitionsOperations, policySetDefinitionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.Delete (operations, policySetDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-111">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-112">ポリシーの名前は、削除する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-112">The name of the policy set definition to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-113">削除、ポリシーは、定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-113">Deletes a policy set definition.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.DeleteAsync (operations, policySetDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-114">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-115">ポリシーの名前は、削除する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-115">The name of the policy set definition to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3561-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3561-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-117">削除、ポリシーは、定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-117">Deletes a policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition Get (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition Get(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPolicySetDefinitionsOperations, policySetDefinitionName As String) As PolicySetDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.Get (operations, policySetDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-118">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-119">ポリシーの名前を取得する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-119">The name of the policy set definition to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-120">ポリシーのセットの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-120">Gets the policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string policySetDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.GetAsync (operations, policySetDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-121">The operations group for this extension method.</span></span>
            </param>
        <param name="policySetDefinitionName">
            <span data-ttu-id="a3561-122">ポリシーの名前を取得する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="a3561-122">The name of the policy set definition to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3561-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3561-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-124">ポリシーのセットの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-124">Gets the policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPolicySetDefinitionsOperations) As IPage(Of PolicySetDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-125">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-126">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-126">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-127">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3561-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3561-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-129">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-129">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPolicySetDefinitionsOperations, nextPageLink As String) As IPage(Of PolicySetDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a3561-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a3561-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-132">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-132">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.PolicySetDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3561-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3561-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a3561-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a3561-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3561-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3561-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3561-136">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3561-136">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>