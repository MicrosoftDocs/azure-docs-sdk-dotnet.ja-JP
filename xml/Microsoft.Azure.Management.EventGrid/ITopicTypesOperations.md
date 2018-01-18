<Type Name="ITopicTypesOperations" FullName="Microsoft.Azure.Management.EventGrid.ITopicTypesOperations">
  <TypeSignature Language="C#" Value="public interface ITopicTypesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITopicTypesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.ITopicTypesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITopicTypesOperations" />
  <TypeSignature Language="F#" Value="type ITopicTypesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0648-101">TopicTypesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d0648-101">TopicTypesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt; GetWithHttpMessagesAsync (string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt; GetWithHttpMessagesAsync(string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicTypesOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;" Usage="iTopicTypesOperations.GetWithHttpMessagesAsync (topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="topicTypeName">
            <span data-ttu-id="d0648-102">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="d0648-102">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d0648-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d0648-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0648-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d0648-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0648-105">トピックの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="d0648-105">Get a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d0648-106">トピックの種類に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d0648-106">Get information about a topic type</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d0648-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d0648-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d0648-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt; ListEventTypesWithHttpMessagesAsync (string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt; ListEventTypesWithHttpMessagesAsync(string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicTypesOperations.ListEventTypesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventTypesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt;" Usage="iTopicTypesOperations.ListEventTypesWithHttpMessagesAsync (topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="topicTypeName">
            <span data-ttu-id="d0648-110">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="d0648-110">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d0648-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d0648-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0648-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d0648-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0648-113">イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="d0648-113">List event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d0648-114">トピックの種類の一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="d0648-114">List event types for a topic type</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d0648-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d0648-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d0648-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicTypesOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;&gt;" Usage="iTopicTypesOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="d0648-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d0648-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0648-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d0648-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0648-120">一覧のトピックの種類</span><span class="sxs-lookup"><span data-stu-id="d0648-120">List topic types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d0648-121">すべての登録されているトピックの種類を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d0648-121">List all registered topic types</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d0648-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d0648-123">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-123">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d0648-124">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d0648-124">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>