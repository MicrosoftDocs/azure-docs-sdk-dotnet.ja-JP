<Type Name="HybridConnectionListener" FullName="Microsoft.Azure.Relay.HybridConnectionListener">
  <TypeSignature Language="C#" Value="public class HybridConnectionListener : Microsoft.Azure.Relay.IConnectionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionListener extends System.Object implements class Microsoft.Azure.Relay.IConnectionStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionListener" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionListener&#xA;Implements IConnectionStatus" />
  <TypeSignature Language="F#" Value="type HybridConnectionListener = class&#xA;    interface IConnectionStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Relay.IConnectionStatus</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4d7e0-101">リモート クライアントから HybridConnections の受け入れをリスナーを提供します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-101">Provides a listener for accepting HybridConnections from remote clients.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : string -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4d7e0-102">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-102">The connection string to use.</span></span>  <span data-ttu-id="4d7e0-103">この接続文字列には、EntityPath プロパティを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-103">This connection string must include the EntityPath property.</span></span></param>
        <summary><span data-ttu-id="4d7e0-104">新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />指定された接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-104">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="4d7e0-105">新しく作成された<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-105">The newly created <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4d7e0-106">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-106">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener (connectionString, path)" />
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
        <param name="connectionString"><span data-ttu-id="4d7e0-107">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-107">The connection string used.</span></span> <span data-ttu-id="4d7e0-108">この接続文字列には、EntityPath プロパティは含めないでください。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-108">This connection string must not include the EntityPath property.</span></span></param>
        <param name="path"><span data-ttu-id="4d7e0-109">HybridConnection へのパス。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-109">The path to the HybridConnection.</span></span></param>
        <summary><span data-ttu-id="4d7e0-110">新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />から接続文字列と HybridConection パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-110">Creates a new instance of <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> from a connection string and the specified HybridConection path.</span></span> <span data-ttu-id="4d7e0-111">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-111">Use this overload only when the connection string does not use the <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="4d7e0-112">作成された <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-112">The created <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4d7e0-113">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-113">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionListener (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionListener : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionListener" Usage="new Microsoft.Azure.Relay.HybridConnectionListener (address, tokenProvider)" />
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
        <param name="address"><span data-ttu-id="4d7e0-114">HybridConnections をリッスンするアドレス。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-114">The address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="4d7e0-115">このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-115">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="4d7e0-116">このリスナーを ServiceBus に接続するため TokenProvider です。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-116">The TokenProvider for connecting this listener to ServiceBus.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-117">HybridConnections を受け入れるための新しい HybridConnectionListener インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-117">Create a new HybridConnectionListener instance for accepting HybridConnections.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; AcceptConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; AcceptConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.AcceptConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.AcceptConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionListener.AcceptConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-118">リモート クライアントとストリームを返します。 によって開始された新しい HybridConnection を受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-118">Accepts a new HybridConnection which was initiated by a remote client and returns the Stream.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext,System.Threading.Tasks.Task&lt;bool&gt;&gt; AcceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.Relay.RelayedHttpListenerContext, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; AcceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.AcceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptHandler As Func(Of RelayedHttpListenerContext, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.AcceptHandler : Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext, System.Threading.Tasks.Task&lt;bool&gt;&gt; with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionListener.AcceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.Relay.RelayedHttpListenerContext,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-119">要求ヘッダーを検査、応答ヘッダーの制御、受け入れるか、web ソケットのアップグレード要求を拒否するかどうかを決定するカスタム ハンドラーのインストールを許可および拒否する場合は、ステータス コードと説明を制御します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-119">Allows installing a custom handler which can inspect request headers, control response headers, decide whether to accept or reject a web-socket upgrade request, and control the status code/description if rejecting.</span></span>
            <span data-ttu-id="4d7e0-120">AcceptHandler は拒否するには、クライアントの要求または false をそのまま使用する場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-120">The AcceptHandler should return true to accept a client request or false to reject.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionListener.Address" />
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
            <span data-ttu-id="4d7e0-121">HybridConnections をリッスンするアドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-121">Gets the address on which to listen for HybridConnections.</span></span>  <span data-ttu-id="4d7e0-122">このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-122">This address should be of the format "sb://contoso.servicebus.windows.net/yourhybridconnection".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-123">閉じる、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />既定のタイムアウトを使用します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-123">Closes the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> using the default timeout.</span></span>
            <span data-ttu-id="4d7e0-124">接続文字列で指定しない限り、既定値は 1 分にします。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-124">Unless specified in the connection string the default is 1 minute.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4d7e0-125">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-125">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-126">閉じる、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />指定されたキャンセル トークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-126">Closes the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> using the provided CancellationToken.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.CloseAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : TimeSpan -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.CloseAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;CloseAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="4d7e0-127">観察するタイムアウトします。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-127">A timeout to observe.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-128">閉じる、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />提供されているタイムアウトを使用しています。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-128">Closes the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> using the provided timeout.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connecting">
      <MemberSignature Language="C#" Value="public event EventHandler Connecting;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Connecting" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Connecting" />
      <MemberSignature Language="VB.NET" Value="Public Event Connecting As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Connecting : EventHandler " Usage="member this.Connecting : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Connecting</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-129">リスナーが ServiceBus 接続損失後に再接続しようとするときに発生します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-129">Raised when the Listener is attempting to reconnect with ServiceBus after a connection loss.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionListener.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;GetRuntimeInformationAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-130">取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の既定のタイムアウトを使用してこの HybridConnection エンティティです。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-130">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the default timeout.</span></span>
            <span data-ttu-id="4d7e0-131">接続文字列で指定しない限り、既定値は 1 分にします。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-131">Unless specified in the connection string the default is 1 minute.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionListener.GetRuntimeInformationAsync cancellationToken" />
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
        <param name="cancellationToken"><span data-ttu-id="4d7e0-132">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-132">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-133">取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の指定されたキャンセル トークンを使用してこの HybridConnection エンティティです。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-133">Gets the <see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" /> for this HybridConnection entity using the provided CancellationToken.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOnline">
      <MemberSignature Language="C#" Value="public bool IsOnline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOnline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.IsOnline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOnline As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOnline : bool" Usage="Microsoft.Azure.Relay.HybridConnectionListener.IsOnline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d7e0-134">接続がオンラインかどうかを決定する値を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-134">Gets a value that determines whether the connection is online.</span></span></summary>
        <value><span data-ttu-id="4d7e0-135">接続がアライブとオンライン以外の場合は true現在のネットワークの場所から Azure サービス バスに接続されていない場合は false。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-135">true if the connection is alive and online; false if there is no connectivity towards the Azure Service Bus from the current network location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastError">
      <MemberSignature Language="C#" Value="public Exception LastError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception LastError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.LastError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastError As Exception" />
      <MemberSignature Language="F#" Value="member this.LastError : Exception" Usage="Microsoft.Azure.Relay.HybridConnectionListener.LastError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4d7e0-136">オフラインの状態からの接続を再確立する際に発生した最後のエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-136">Retrieves the last error encountered when trying to reestablish the connection from the offline state.</span></span></summary>
        <value><span data-ttu-id="4d7e0-137">返します、<see cref="T:System.Exception" />最後のエラーを格納しています。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-137">Returns a <see cref="T:System.Exception" /> that contains the last error.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="public event EventHandler Offline;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Offline" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Offline" />
      <MemberSignature Language="VB.NET" Value="Public Event Offline As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Offline : EventHandler " Usage="member this.Offline : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Offline</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-138">リスナーが ServiceBus (再) 接続をしようとするは不要になったときに発生します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-138">Raised when the Listener will no longer be attempting to (re)connect with ServiceBus.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="public event EventHandler Online;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler Online" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Relay.HybridConnectionListener.Online" />
      <MemberSignature Language="VB.NET" Value="Public Event Online As EventHandler " />
      <MemberSignature Language="F#" Value="member this.Online : EventHandler " Usage="member this.Online : System.EventHandler " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.Azure.Relay.IConnectionStatus.Online</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-139">リスナーが正常に ServiceBus に接続されているときに発生します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-139">Raised when the Listener has successfully connected with ServiceBus</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-140">開く、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />し、ServiceBus にリスナーとして登録します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-140">Opens the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> and registers it as a listener in ServiceBus.</span></span>
            <span data-ttu-id="4d7e0-141">接続文字列で指定しない限り、既定値は 1 分にします。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-141">Unless specified in the connection string the default is 1 minute.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;OpenAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4d7e0-142">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-142">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-143">開く、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />し、ServiceBus にリスナーとして登録します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-143">Opens the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> and registers it as a listener in ServiceBus.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task OpenAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.OpenAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.OpenAsync : TimeSpan -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionListener.OpenAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionListener/&lt;OpenAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="4d7e0-144">観察するタイムアウトします。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-144">A timeout to observe.</span></span></param>
        <summary>
            <span data-ttu-id="4d7e0-145">開く、<see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" />し、ServiceBus にリスナーとして登録します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-145">Opens the <see cref="T:Microsoft.Azure.Relay.HybridConnectionListener" /> and registers it as a listener in ServiceBus.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionListener.Proxy" />
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
            <span data-ttu-id="4d7e0-146">取得または ServiceBus に接続するためのプロキシ情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-146">Gets or sets proxy information for connecting to ServiceBus.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.TokenProvider TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionListener.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionListener.TokenProvider" />
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
            <span data-ttu-id="4d7e0-147">この HybridConnection リスナーを認証するため、TokenProvider を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-147">Gets the TokenProvider for authenticating this HybridConnection listener.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionListener.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="hybridConnectionListener.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d7e0-148">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-148">Returns a string that represents the current object.</span></span>  <span data-ttu-id="4d7e0-149">エンド ツー エンドの相関関係の TrackingId が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4d7e0-149">Includes a TrackingId for end to end correlation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>