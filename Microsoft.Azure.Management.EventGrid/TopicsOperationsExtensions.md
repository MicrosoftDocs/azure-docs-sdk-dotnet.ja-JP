<Type Name="TopicsOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopicsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopicsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopicsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopicsOperationsExtensions = class" />
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
            <span data-ttu-id="af2e4-101">TopicsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="af2e4-101">Extension methods for TopicsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic BeginCreateOrUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic BeginCreateOrUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, topicInfo As Topic) As Topic" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, topicName, topicInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-103">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-103">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-104">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-104">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="af2e4-105">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="af2e4-105">Topic information</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-106">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="af2e4-106">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-107">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-107">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, topicName, topicInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-109">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-109">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-110">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-110">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="af2e4-111">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="af2e4-111">Topic information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-113">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="af2e4-113">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-114">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-114">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ITopicsOperations, resourceGroupName As String, topicName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDelete (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-116">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-116">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-117">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-117">Name of the topic</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-118">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="af2e4-118">Delete a topic</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="af2e4-119">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-119">Delete existing topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-121">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-121">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-122">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-122">Name of the topic</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-124">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="af2e4-124">Delete a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-125">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-125">Delete existing topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic BeginUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic BeginUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, Optional tags As IDictionary(Of String, String) = null) As Topic" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdate (operations, resourceGroupName, topicName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-127">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-127">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-128">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-128">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="af2e4-129">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="af2e4-129">Tags of the resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-130">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-130">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-131">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-131">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; BeginUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, topicName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-133">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-133">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-134">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-134">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="af2e4-135">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="af2e4-135">Tags of the resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-137">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-137">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-138">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-138">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic CreateOrUpdate (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic CreateOrUpdate(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITopicsOperations, resourceGroupName As String, topicName As String, topicInfo As Topic) As Topic" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, topicName, topicInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-140">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-140">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-141">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-141">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="af2e4-142">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="af2e4-142">Topic information</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-143">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="af2e4-143">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-144">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-144">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, topicName, topicInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-146">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-146">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-147">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-147">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="af2e4-148">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="af2e4-148">Topic information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-150">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="af2e4-150">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-151">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-151">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Delete(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITopicsOperations, resourceGroupName As String, topicName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Delete (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-153">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-153">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-154">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-154">Name of the topic</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-155">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="af2e4-155">Delete a topic</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="af2e4-156">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-156">Delete existing topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.DeleteAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-158">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-158">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-159">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-159">Name of the topic</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-161">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="af2e4-161">Delete a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-162">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-162">Delete existing topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic Get (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic Get(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITopicsOperations, resourceGroupName As String, topicName As String) As Topic" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Get (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-164">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-164">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-165">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-165">Name of the topic</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-166">トピックを取得します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-166">Get a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-167">トピックのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-167">Get properties of a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.GetAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-169">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-169">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-170">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-170">Name of the topic</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-172">トピックを取得します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-172">Get a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-173">トピックのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-173">Get properties of a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListByResourceGroup (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListByResourceGroup(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As ITopicsOperations, resourceGroupName As String) As IEnumerable(Of Topic)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-175">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-175">The name of the resource group within the user's subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-176">リソース グループ下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="af2e4-176">List topics under a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-177">リソース グループの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-177">List all the topics under a resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-179">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-179">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-181">リソース グループ下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="af2e4-181">List topics under a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-182">リソース グループの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-182">List all the topics under a resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListBySubscription (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; ListBySubscription(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscription(Microsoft.Azure.Management.EventGrid.ITopicsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscription (operations As ITopicsOperations) As IEnumerable(Of Topic)" />
      <MemberSignature Language="F#" Value="static member ListBySubscription : Microsoft.Azure.Management.EventGrid.ITopicsOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-183">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-184">Azure サブスクリプションの下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="af2e4-184">List topics under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-185">Azure サブスクリプションの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-185">List all the topics under an Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-186">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-188">Azure サブスクリプションの下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="af2e4-188">List topics under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-189">Azure サブスクリプションの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-189">List all the topics under an Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt; ListEventTypes(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypes(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventTypes (operations As ITopicsOperations, resourceGroupName As String, providerNamespace As String, resourceTypeName As String, resourceName As String) As IEnumerable(Of EventType)" />
      <MemberSignature Language="F#" Value="static member ListEventTypes : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypes (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-191">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-191">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="af2e4-192">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="af2e4-192">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="af2e4-193">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-193">Name of the topic type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="af2e4-194">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-194">Name of the topic</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-195">トピック イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="af2e4-195">List topic event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-196">トピックの一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="af2e4-196">List event types for a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt; ListEventTypesAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypesAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventTypesAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListEventTypesAsync (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListEventTypesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-198">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-198">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="af2e4-199">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="af2e4-199">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="af2e4-200">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-200">Name of the topic type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="af2e4-201">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-201">Name of the topic</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-203">トピック イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="af2e4-203">List topic event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-204">トピックの一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="af2e4-204">List event types for a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharedAccessKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys ListSharedAccessKeys (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys ListSharedAccessKeys(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeys(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSharedAccessKeys (operations As ITopicsOperations, resourceGroupName As String, topicName As String) As TopicSharedAccessKeys" />
      <MemberSignature Language="F#" Value="static member ListSharedAccessKeys : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeys (operations, resourceGroupName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-205">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-206">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-206">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-207">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-207">Name of the topic</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-208">トピックのキーの一覧表示</span><span class="sxs-lookup"><span data-stu-id="af2e4-208">List keys for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-209">トピックへの公開に使用される 2 つのキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-209">List the two keys used to publish to a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharedAccessKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; ListSharedAccessKeysAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; ListSharedAccessKeysAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeysAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSharedAccessKeysAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.ListSharedAccessKeysAsync (operations, resourceGroupName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;ListSharedAccessKeysAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-211">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-211">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-212">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-212">Name of the topic</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-214">トピックのキーの一覧表示</span><span class="sxs-lookup"><span data-stu-id="af2e4-214">List keys for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-215">トピックへの公開に使用される 2 つのキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-215">List the two keys used to publish to a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys RegenerateKey (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys RegenerateKey(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As ITopicsOperations, resourceGroupName As String, topicName As String, keyName As String) As TopicSharedAccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKey (operations, resourceGroupName, topicName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-217">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-217">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-218">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-218">Name of the topic</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="af2e4-219">Key1、key2 または再生成するキーの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-219">Key name to regenerate key1 or key2</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-220">トピックのキーを再生成</span><span class="sxs-lookup"><span data-stu-id="af2e4-220">Regenerate key for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-221">トピックの共有アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-221">Regenerate a shared access key for a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, topicName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-223">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-223">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-224">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-224">Name of the topic</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="af2e4-225">Key1、key2 または再生成するキーの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-225">Key name to regenerate key1 or key2</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-227">トピックのキーを再生成</span><span class="sxs-lookup"><span data-stu-id="af2e4-227">Regenerate key for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-228">トピックの共有アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-228">Regenerate a shared access key for a topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.Topic Update (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.Topic Update(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Update(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ITopicsOperations, resourceGroupName As String, topicName As String, Optional tags As IDictionary(Of String, String) = null) As Topic" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.Topic" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.Update (operations, resourceGroupName, topicName, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.Topic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-230">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-230">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-231">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-231">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="af2e4-232">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="af2e4-232">Tags of the resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-233">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-233">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-234">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-234">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt; UpdateAsync (this Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt; UpdateAsync(class Microsoft.Azure.Management.EventGrid.ITopicsOperations operations, string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventGrid.ITopicsOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventGrid.ITopicsOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;" Usage="Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions.UpdateAsync (operations, resourceGroupName, topicName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.TopicsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="af2e4-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="af2e4-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="af2e4-236">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="af2e4-236">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="af2e4-237">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="af2e4-237">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="af2e4-238">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="af2e4-238">Tags of the resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="af2e4-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="af2e4-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="af2e4-240">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-240">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="af2e4-241">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="af2e4-241">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>