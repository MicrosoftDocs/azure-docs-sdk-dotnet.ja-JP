<Type Name="HybridConnectionClient" FullName="Microsoft.Azure.Relay.HybridConnectionClient">
  <TypeSignature Language="C#" Value="public class HybridConnectionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionClient" />
  <TypeSignature Language="F#" Value="type HybridConnectionClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e2f6-101">新しい送信側 HybridConnections を開始するため、クライアントを提供します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-101">Provides a client for initiating new send-side HybridConnections.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="8e2f6-102">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-102">The connection string to use.</span></span>  <span data-ttu-id="8e2f6-103">この接続文字列には、EntityPath プロパティを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-103">This connection string must include the EntityPath property.</span></span></param>
        <summary><span data-ttu-id="8e2f6-104">新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />指定された接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-104">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="8e2f6-105">新しく作成された<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-105">The newly created <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8e2f6-106">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-106">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="8e2f6-107">HybridConnections をリッスンするアドレス。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-107">The address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="8e2f6-108">このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-108">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span></param>
        <summary>
            <span data-ttu-id="8e2f6-109">クライアント認証は必要ありません HybridConnections を開始するための新しい HybridConnectionClient インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-109">Create a new HybridConnectionClient instance for initiating HybridConnections where no client authentication is required.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (connectionString, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="8e2f6-110">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-110">The connection string used.</span></span> <span data-ttu-id="8e2f6-111">この接続文字列には、EntityPath プロパティは含めないでください。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-111">This connection string must not include the EntityPath property.</span></span></param>
        <param name="path"><span data-ttu-id="8e2f6-112">HybridConnection へのパス。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-112">The path to the HybridConnection.</span></span></param>
        <summary><span data-ttu-id="8e2f6-113">新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />から接続文字列と HybridConection パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-113">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" /> from a connection string and the specified HybridConection path.</span></span> <span data-ttu-id="8e2f6-114">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-114">Use this overload only when the connection string does not use the <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="8e2f6-115">作成された <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-115">The created <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="8e2f6-116">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-116">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.Relay.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="8e2f6-117">HybridConnections をリッスンするアドレス。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-117">The address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="8e2f6-118">このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-118">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="8e2f6-119">ServiceBus に接続するため TokenProvider です。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-119">The TokenProvider for connecting to ServiceBus.</span></span></param>
        <summary>
            <span data-ttu-id="8e2f6-120">クライアント認証と HybridConnections を開始するための新しい HybridConnectionClient インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-120">Create a new HybridConnectionClient instance for initiating HybridConnections with client authentication.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-121">この HybridConnection を使用して接続のアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-121">Gets the address of this HybridConnection to connect through.</span></span> <span data-ttu-id="8e2f6-122">HybridConnections をリッスンするアドレス。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-122">The address on which to listen for HybridConnections.</span></span>
            <span data-ttu-id="8e2f6-123">このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-123">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.CreateConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.CreateConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionClient.CreateConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;CreateConnectionAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-124">新しい送信側 HybridConnection を確立し、ストリームを返します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-124">Establishes a new send-side HybridConnection and returns the Stream.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;GetRuntimeInformationAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-125">取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の既定のタイムアウトを使用してこの HybridConnection エンティティです。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-125">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the default timeout.</span></span>
            <span data-ttu-id="8e2f6-126">接続文字列で指定しない限り、既定値は 1 分にします。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-126">Unless specified in the connection string the default is 1 minute.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="8e2f6-127">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-127">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="8e2f6-128">取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の指定されたキャンセル トークンを使用してこの HybridConnection エンティティです。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-128">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the provided CancellationToken.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-129">取得または、HybridConnection を接続するときに使用されるタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-129">Gets or sets the timeout used when connecting a HybridConnection.</span></span>  <span data-ttu-id="8e2f6-130">既定値は、70 秒です。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-130">Default value is 70 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.IWebProxy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-131">取得または ServiceBus に接続するためのプロキシ情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-131">Gets or sets proxy information for connecting to ServiceBus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.TokenProvider TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e2f6-132">HybridConnections を認証するため、TokenProvider を取得します。</span><span class="sxs-lookup"><span data-stu-id="8e2f6-132">Gets the TokenProvider for authenticating HybridConnections.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>