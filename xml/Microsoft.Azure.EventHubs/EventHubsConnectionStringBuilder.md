<Type Name="EventHubsConnectionStringBuilder" FullName="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubsConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubsConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type EventHubsConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1433-101">EventHubsConnectionStringBuilder は、Event Hubs のエンティティとの通信を確立できる接続文字列を構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="b1433-101">EventHubsConnectionStringBuilder can be used to construct a connection string which can establish communication with Event Hubs entities.</span></span>
            <span data-ttu-id="b1433-102">既存の接続文字列で基本的な検証を実行するも使用できます。</span><span class="sxs-lookup"><span data-stu-id="b1433-102">It can also be used to perform basic validation on an existing connection string.</span></span>
            <span data-ttu-id="b1433-103"><para />接続文字列は、基本的に、文字列で区切られたキーと値のペアで構成されている「;」です。</span><span class="sxs-lookup"><span data-stu-id="b1433-103"><para /> A connection string is basically a string consisted of key-value pair separated by ";".</span></span> <span data-ttu-id="b1433-104">基本形式は"&lt;キー&gt;=&lt;値&gt;[;&lt;キー&gt;=&lt;値&gt;]"サポートされているキー名が次のような場所:<para />エンドポイントにイベント ハブ名前空間を含む URL <para /> EntityPath - Event Hub へのパスエンティティ<para />SharedAccessKeyName - 名前空間、またはエンティティの対応する共有アクセス ポリシーのルールにキーの名前。</span><span class="sxs-lookup"><span data-stu-id="b1433-104">Basic format is "&lt;key&gt;=&lt;value&gt;[;&lt;key&gt;=&lt;value&gt;]" where supported key name are as follow: <para /> Endpoint - the URL that contains the Event Hubs namespace <para /> EntityPath - the path to the Event Hub entity <para /> SharedAccessKeyName - the key name to the corresponding shared access policy rule for the namespace, or entity.</span></span>
            <span data-ttu-id="b1433-105"><para />SharedAccessKey -、対応する共有アクセス ポリシー規則の名前空間またはエンティティのキー。</span><span class="sxs-lookup"><span data-stu-id="b1433-105"><para /> SharedAccessKey - the key for the corresponding shared access policy rule of the namespace or entity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="b1433-106">サンプル コード: </span><span class="sxs-lookup"><span data-stu-id="b1433-106">Sample code:</span></span>
            <code>
            var connectionStringBuiler = new EventHubsConnectionStringBuilder(
                "amqps://EventHubsNamespaceName.servicebus.windows.net", 
                "EventHubsEntityName", // Event Hub Name 
                "SharedAccessSignatureKeyName", 
                "SharedAccessSignatureKey");
             string connectionString = connectionStringBuiler.ToString();
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="b1433-107">イベント ハブの接続文字列</span><span class="sxs-lookup"><span data-stu-id="b1433-107">Event Hubs ConnectionString</span></span></param>
        <summary>
            <span data-ttu-id="b1433-108">ConnectionString の形式: エンドポイント = sb://namespace_DNS_Name です。EntityPath EVENT_HUB_NAME; を =SharedAccessKeyName = SHARED_ACCESS_KEY_NAME です。SharedAccessKey SHARED_ACCESS_KEY を =</span><span class="sxs-lookup"><span data-stu-id="b1433-108">ConnectionString format: Endpoint=sb://namespace_DNS_Name;EntityPath=EVENT_HUB_NAME;SharedAccessKeyName=SHARED_ACCESS_KEY_NAME;SharedAccessKey=SHARED_ACCESS_KEY</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="b1433-109">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="b1433-109">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="b1433-110">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="b1433-110">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="b1433-111">エンティティのパスまたは Event Hub の名前。</span><span class="sxs-lookup"><span data-stu-id="b1433-111">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessKeyName"><span data-ttu-id="b1433-112">共有アクセス キーの名前</span><span class="sxs-lookup"><span data-stu-id="b1433-112">Shared Access Key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="b1433-113">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="b1433-113">Shared Access Key</span></span></param>
        <summary>
            <span data-ttu-id="b1433-114">使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="b1433-114">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessSignature, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessSignature, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessSignature As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessSignature, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessSignature" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="b1433-115">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="b1433-115">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="b1433-116">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="b1433-116">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="b1433-117">エンティティのパスまたは Event Hub の名前。</span><span class="sxs-lookup"><span data-stu-id="b1433-117">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessSignature"><span data-ttu-id="b1433-118">Shared Access Signature</span><span class="sxs-lookup"><span data-stu-id="b1433-118">Shared Access Signature</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="b1433-119">Event Hubs の操作の操作のタイムアウト</span><span class="sxs-lookup"><span data-stu-id="b1433-119">Operation timeout for Event Hubs operations</span></span></param>
        <summary>
            <span data-ttu-id="b1433-120">使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="b1433-120">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsConnectionStringBuilder (Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpointAddress, string entityPath, string sharedAccessKeyName, string sharedAccessKey, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.#ctor(System.Uri,System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointAddress As Uri, entityPath As String, sharedAccessKeyName As String, sharedAccessKey As String, operationTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder : Uri * string * string * string * TimeSpan -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="new Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder (endpointAddress, entityPath, sharedAccessKeyName, sharedAccessKey, operationTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="sharedAccessKeyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="b1433-121">Event Hubs の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="b1433-121">Fully qualified domain name for Event Hubs.</span></span> <span data-ttu-id="b1433-122">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="b1433-122">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="b1433-123">エンティティのパスまたは Event Hub の名前。</span><span class="sxs-lookup"><span data-stu-id="b1433-123">Entity path or Event Hub name.</span></span></param>
        <param name="sharedAccessKeyName"><span data-ttu-id="b1433-124">共有アクセス キーの名前</span><span class="sxs-lookup"><span data-stu-id="b1433-124">Shared Access Key name</span></span></param>
        <param name="sharedAccessKey"><span data-ttu-id="b1433-125">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="b1433-125">Shared Access Key</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="b1433-126">Event Hubs の操作の操作のタイムアウト</span><span class="sxs-lookup"><span data-stu-id="b1433-126">Operation timeout for Event Hubs operations</span></span></param>
        <summary>
            <span data-ttu-id="b1433-127">使用できる接続文字列を作成します。<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span><span class="sxs-lookup"><span data-stu-id="b1433-127">Build a connection string consumable by <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As EventHubsConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" Usage="eventHubsConnectionStringBuilder.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b1433-128">現在のオブジェクトのクローンを作成<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />です。</span><span class="sxs-lookup"><span data-stu-id="b1433-128">Creates a cloned object of the current <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b1433-129">新しい<see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></span><span class="sxs-lookup"><span data-stu-id="b1433-129">A new <see cref="T:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-130">取得または Event Hubs のエンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="b1433-130">Gets or sets the Event Hubs endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-131">接続文字列からエンティティ path の値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b1433-131">Get the entity path value from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-132">関連するについて、呼び出し元に通知するエラーがある状況で OperationTimeout が適用されます。<see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></span><span class="sxs-lookup"><span data-stu-id="b1433-132">OperationTimeout is applied in erroneous situations to notify the caller about the relevant <see cref="T:Microsoft.Azure.EventHubs.EventHubsException" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKey">
      <MemberSignature Language="C#" Value="public string SasKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKey As String" />
      <MemberSignature Language="F#" Value="member this.SasKey : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-133">接続文字列からの共有アクセス ポリシー キーの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b1433-133">Get the shared access policy key value from the connection string</span></span>
            </summary>
        <value><span data-ttu-id="b1433-134">共有アクセス署名キー</span><span class="sxs-lookup"><span data-stu-id="b1433-134">Shared Access Signature key</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasKeyName">
      <MemberSignature Language="C#" Value="public string SasKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SasKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SasKeyName : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SasKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-135">接続文字列から、共有アクセス ポリシーの所有者名を取得します。</span><span class="sxs-lookup"><span data-stu-id="b1433-135">Get the shared access policy owner name from the connection string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-136">取得または SAS アクセス トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="b1433-136">Gets or sets the SAS access token.</span></span>
            </summary>
        <value><span data-ttu-id="b1433-137">Shared Access Signature</span><span class="sxs-lookup"><span data-stu-id="b1433-137">Shared Access Signature</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="eventHubsConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b1433-138">イベント ハブ Namespace への接続に使用できる相互操作可能な接続文字列を返します</span><span class="sxs-lookup"><span data-stu-id="b1433-138">Returns an interoperable connection string that can be used to connect to Event Hubs Namespace</span></span>
            </summary>
        <returns><span data-ttu-id="b1433-139">接続文字列</span><span class="sxs-lookup"><span data-stu-id="b1433-139">the connection string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.EventHubs.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.Azure.EventHubs.TransportType with get, set" Usage="Microsoft.Azure.EventHubs.EventHubsConnectionStringBuilder.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b1433-140">トランスポートのクライアント接続の種類。</span><span class="sxs-lookup"><span data-stu-id="b1433-140">Transport type for the client connection.</span></span>
            <span data-ttu-id="b1433-141">使用可能なオプションは、Amqp AmqpWebSockets です。</span><span class="sxs-lookup"><span data-stu-id="b1433-141">Avaiable options are Amqp and AmqpWebSockets.</span></span>
            <span data-ttu-id="b1433-142">Amqp が指定されていない場合に既定値です。</span><span class="sxs-lookup"><span data-stu-id="b1433-142">Defaults to Amqp if not specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>