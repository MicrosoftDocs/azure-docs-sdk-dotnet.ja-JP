<Type Name="SubscriptionDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsOperationsExtensions = class" />
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
            <span data-ttu-id="10679-101">SubscriptionDefinitionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="10679-101">Extension methods for SubscriptionDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition BeginCreate(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreate (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-102">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-103">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-103">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="10679-104">サブスクリプション定義の作成。</span><span class="sxs-lookup"><span data-stu-id="10679-104">The subscription definition creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-105">Azure サブスクリプションの定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="10679-105">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; BeginCreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.BeginCreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-106">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-107">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-107">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="10679-108">サブスクリプション定義の作成。</span><span class="sxs-lookup"><span data-stu-id="10679-108">The subscription definition creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-110">Azure サブスクリプションの定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="10679-110">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Create(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String, body As SubscriptionDefinition) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Create (operations, subscriptionDefinitionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-111">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-112">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-112">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="10679-113">サブスクリプション定義の作成。</span><span class="sxs-lookup"><span data-stu-id="10679-113">The subscription definition creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-114">Azure サブスクリプションの定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="10679-114">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; CreateAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.CreateAsync (operations, subscriptionDefinitionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-115">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-116">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-116">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="body">
            <span data-ttu-id="10679-117">サブスクリプション定義の作成。</span><span class="sxs-lookup"><span data-stu-id="10679-117">The subscription definition creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-119">Azure サブスクリプションの定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="10679-119">Create an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition Get(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionDefinitionsOperations, subscriptionDefinitionName As String) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.Get (operations, subscriptionDefinitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-120">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-121">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-121">The name of the Azure subscription definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-122">Azure サブスクリプション定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="10679-122">Get an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string subscriptionDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetAsync (operations, subscriptionDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="subscriptionDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-123">The operations group for this extension method.</span></span>
            </param>
        <param name="subscriptionDefinitionName">
            <span data-ttu-id="10679-124">Azure サブスクリプション定義の名前。</span><span class="sxs-lookup"><span data-stu-id="10679-124">The name of the Azure subscription definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-126">Azure サブスクリプション定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="10679-126">Get an Azure subscription definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition GetOperationStatus(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As ISubscriptionDefinitionsOperations, operationId As Guid) As SubscriptionDefinition" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatus (operations, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-127">The operations group for this extension method.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="10679-128">操作 ID、生成する推奨設定の応答ヘッダーに Location フィールドから確認できます。</span><span class="sxs-lookup"><span data-stu-id="10679-128">The operation ID, which can be found from the Location field in the generate recommendation response header.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-129">サブスクリプション定義 PUT 操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="10679-129">Retrieves the status of the subscription definition PUT operation.</span></span> <span data-ttu-id="10679-130">この API の URI は、応答ヘッダーの [場所] フィールドで返されます。</span><span class="sxs-lookup"><span data-stu-id="10679-130">The URI of this API is returned in the Location field of the response header.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, Guid operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; GetOperationStatusAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.GetOperationStatusAsync (operations, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;GetOperationStatusAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-131">The operations group for this extension method.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="10679-132">操作 ID、生成する推奨設定の応答ヘッダーに Location フィールドから確認できます。</span><span class="sxs-lookup"><span data-stu-id="10679-132">The operation ID, which can be found from the Location field in the generate recommendation response header.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-134">サブスクリプション定義 PUT 操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="10679-134">Retrieves the status of the subscription definition PUT operation.</span></span> <span data-ttu-id="10679-135">この API の URI は、応答ヘッダーの [場所] フィールドで返されます。</span><span class="sxs-lookup"><span data-stu-id="10679-135">The URI of this API is returned in the Location field of the response header.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; List(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISubscriptionDefinitionsOperations) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-136">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-137">サブスクリプション Id で、Azure サブスクリプションの定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="10679-137">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-138">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-140">サブスクリプション Id で、Azure サブスクリプションの定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="10679-140">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISubscriptionDefinitionsOperations, nextPageLink As String) As IPage(Of SubscriptionDefinition)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="10679-142">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="10679-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-143">サブスクリプション Id で、Azure サブスクリプションの定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="10679-143">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.SubscriptionDefinitionsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ISubscriptionDefinitionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="10679-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="10679-144">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="10679-145">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="10679-145">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="10679-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="10679-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10679-147">サブスクリプション Id で、Azure サブスクリプションの定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="10679-147">List an Azure subscription definition by subscriptionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>