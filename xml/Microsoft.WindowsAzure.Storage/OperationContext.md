<Type Name="OperationContext" FullName="Microsoft.WindowsAzure.Storage.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d65ea-101">ストレージ サービスに対する要求操作のコンテキストを表し、その実行に関する追加のランタイム情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-101">Represents the context for a request operation against the storage service, and provides additional runtime information about its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.OperationContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-102"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestID">
      <MemberSignature Language="C#" Value="public string ClientRequestID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestID As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestID : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.ClientRequestID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-103">取得またはクライアント要求 ID の設定</span><span class="sxs-lookup"><span data-stu-id="d65ea-103">Gets or sets the client request ID.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-104">Id クライアント要求を含む文字列です。</span><span class="sxs-lookup"><span data-stu-id="d65ea-104">A string containing the client request ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomUserAgent">
      <MemberSignature Language="C#" Value="public string CustomUserAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomUserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomUserAgent As String" />
      <MemberSignature Language="F#" Value="member this.CustomUserAgent : string with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.CustomUserAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="d65ea-105">インスタンスごと (グローバル) SendingRequestEvent を使用して UserAgent 値が変更された場合、この値はオーバーライドされます。</span><span class="sxs-lookup"><span data-stu-id="d65ea-105">This value will be overridden if the UserAgent value is modified via SendingRequestEvent (per instance or global).</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultLogLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype Microsoft.WindowsAzure.Storage.LogLevel DefaultLogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DefaultLogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.DefaultLogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.DefaultLogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-106">取得または設定の後に作成されるインスタンスに使用する既定のログ レベル、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="d65ea-106">Gets or sets the default logging level to be used for subsequently created instances of the <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> class.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-107">型の値<see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />どのイベントによってログに記録既定のインスタンスを指定する、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="d65ea-107">A value of type <see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" /> that specifies which events are logged by default by instances of the <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-108">取得または操作の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-108">Gets or sets the end time of the operation.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-109">A<see cref="T:System.DateTime" />操作の終了時刻を示す値。</span><span class="sxs-lookup"><span data-stu-id="d65ea-109">A <see cref="T:System.DateTime" /> value indicating the end time of the operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRequestCompleted">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-110">応答が完全に受信および処理後に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-110">Occurs after a response has been fully received and processed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalResponseReceived">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-111">ダウンロードまたは応答がすべて処理する前に、サーバーから受信したときに発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-111">Occurs when a response is received from the server, before any processing or downloading.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalRetrying">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalRetrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalRetrying" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalRetrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalRetrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalRetrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-112">要求が再試行する前に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-112">Occurs before a request is retried</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalSendingRequest">
      <MemberSignature Language="C#" Value="public static event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; GlobalSendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.GlobalSendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Shared Custom Event GlobalSendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.GlobalSendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.GlobalSendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-113">要求が署名する直前に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-113">Occurs immediately before a request is signed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastResult">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult LastResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult LastResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastResult As RequestResult" />
      <MemberSignature Language="F#" Value="member this.LastResult : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LastResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-114">操作で発生した最後の要求の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-114">Gets the last request result encountered for the operation.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-115">A<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />最後の要求の結果を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d65ea-115">A <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> object that represents the last request result.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.LogLevel LogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.LogLevel LogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property LogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.LogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-116">取得または設定のインスタンスに使用するログ記録レベル、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="d65ea-116">Gets or sets the logging level to be used for an instance of the <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> class.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-117">型の値<see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" />によってログに記録するイベントを指定する、<see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="d65ea-117">A value of type <see cref="P:Microsoft.WindowsAzure.Storage.OperationContext.LogLevel" /> that specifies which events are logged by the <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestCompleted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; RequestCompleted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.RequestCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event RequestCompleted As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.RequestCompleted : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.RequestCompleted : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-118">応答が完全に受信および処理後に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-118">Occurs after a response has been fully received and processed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.RequestResult&gt; RequestResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestResults As IList(Of RequestResult)" />
      <MemberSignature Language="F#" Value="member this.RequestResults : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;" Usage="Microsoft.WindowsAzure.Storage.OperationContext.RequestResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.RequestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-119">取得または現在の操作によって作成された要求の結果のセットを設定します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-119">Gets or sets the set of request results that the current operation has created.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-120"><see cref="T:System.Collections.IList" />オブジェクトを含む<see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />を現在の操作によって作成された要求の結果を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d65ea-120">An <see cref="T:System.Collections.IList" /> object that contains <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> objects that represent the request results created by the current operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; ResponseReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.ResponseReceived" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ResponseReceived As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ResponseReceived : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.ResponseReceived : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-121">またはダウンロードする処理前に、サービスから応答を受け取ったときに発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-121">Occurs when a response is received from the service, before any processing or downloading.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrying">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; Retrying" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.Retrying" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event Retrying As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.Retrying : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.Retrying : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-122">要求が再試行する前に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-122">Occurs before a request is retried</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendingRequest">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; SendingRequest" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.OperationContext.SendingRequest" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event SendingRequest As EventHandler(Of RequestEventArgs) " />
      <MemberSignature Language="F#" Value="member this.SendingRequest : EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " Usage="member this.SendingRequest : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.RequestEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-123">要求が署名する直前に発生します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-123">Occurs immediately before a request is signed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-124">取得または操作の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-124">Gets or sets the start time of the operation.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-125">A<see cref="T:System.DateTime" />操作の開始時刻を示す値。</span><span class="sxs-lookup"><span data-stu-id="d65ea-125">A <see cref="T:System.DateTime" /> value indicating the start time of the operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; UserHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; UserHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property UserHeaders As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.UserHeaders : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.OperationContext.UserHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d65ea-126">取得または、プロキシやログ情報など、要求で追加のヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d65ea-126">Gets or sets additional headers on the request, for example, for proxy or logging information.</span></span>
            </summary>
        <value><span data-ttu-id="d65ea-127">A<see cref="T:System.Collections.Generic.IDictionary`2" />追加ヘッダー情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d65ea-127">A <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing additional header information.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>