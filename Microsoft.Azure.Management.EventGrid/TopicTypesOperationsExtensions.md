<Type Name="TopicTypesOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopicTypesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopicTypesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopicTypesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopicTypesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a3a1b-101">TopicTypesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-101">Extension methods for TopicTypesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo Get (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo Get(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITopicTypesOperations, topicTypeName As String) As TopicTypeInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations * string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.Get (operations, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="a3a1b-103">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="a3a1b-103">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-104">トピックの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-104">Get a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-105">トピックの種類に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-105">Get information about a topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.GetAsync (operations, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-106">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="a3a1b-107">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="a3a1b-107">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3a1b-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-109">トピックの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-109">Get a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-110">トピックの種類に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-110">Get information about a topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt; List (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt; List(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.List(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITopicTypesOperations) As IEnumerable(Of TopicTypeInfo)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-111">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-112">一覧のトピックの種類</span><span class="sxs-lookup"><span data-stu-id="a3a1b-112">List topic types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-113">すべての登録されているトピックの種類を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-113">List all registered topic types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt; ListAsync (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt; ListAsync(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListAsync(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-114">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3a1b-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-116">一覧のトピックの種類</span><span class="sxs-lookup"><span data-stu-id="a3a1b-116">List topic types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-117">すべての登録されているトピックの種類を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-117">List all registered topic types</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListEventTypes(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventTypes (operations As ITopicTypesOperations, topicTypeName As String) As IEnumerable(Of EventType)" />
      <MemberSignature Language="F#" Value="static member ListEventTypes : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListEventTypes (operations, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-118">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="a3a1b-119">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="a3a1b-119">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-120">イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="a3a1b-120">List event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-121">トピックの種類の一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="a3a1b-121">List event types for a topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync (this Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync(class Microsoft.Azure.Management.EventGrid.ITopicTypesOperations operations, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListEventTypesAsync(Microsoft.Azure.Management.EventGrid.ITopicTypesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventTypesAsync : Microsoft.Azure.Management.EventGrid.ITopicTypesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions.ListEventTypesAsync (operations, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicTypesOperationsExtensions/&lt;ListEventTypesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a3a1b-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-122">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="a3a1b-123">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="a3a1b-123">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a3a1b-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a3a1b-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a3a1b-125">イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="a3a1b-125">List event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="a3a1b-126">トピックの種類の一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="a3a1b-126">List event types for a topic type</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>