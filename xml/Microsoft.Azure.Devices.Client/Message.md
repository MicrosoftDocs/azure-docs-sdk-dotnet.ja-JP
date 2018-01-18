<Type Name="Message" FullName="Microsoft.Azure.Devices.Client.Message">
  <TypeSignature Language="C#" Value="public sealed class Message : IDisposable, Microsoft.Azure.Devices.Client.IReadOnlyIndicator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Message extends System.Object implements class Microsoft.Azure.Devices.Client.IReadOnlyIndicator, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.Message" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message&#xA;Implements IDisposable, IReadOnlyIndicator" />
  <TypeSignature Language="F#" Value="type Message = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IReadOnlyIndicator</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="08f9b-101">データ構造体は、iot Hub と対話するために使用されるメッセージを表します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-101">The data structure represent the message that is used for interacting with IotHub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-102">本文データのない既定のコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="08f9b-102">Default constructor with no body data</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Message : byte[] -&gt; Microsoft.Azure.Devices.Client.Message" Usage="new Microsoft.Azure.Devices.Client.Message byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray"><span data-ttu-id="08f9b-103">本文ストリームを形成するために使用するバイト配列</span><span class="sxs-lookup"><span data-stu-id="08f9b-103">a byte array which will be used to form the body stream</span></span></param>
        <summary>
            <span data-ttu-id="08f9b-104">入力バイト配列を本文として使用するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="08f9b-104">Constructor which uses the input byte array as the body</span></span>
            </summary>
        <remarks><span data-ttu-id="08f9b-105">ユーザーは、メッセージを送信するときに、変更不可として入力バイト配列を扱う必要があります。</span><span class="sxs-lookup"><span data-stu-id="08f9b-105">user should treat the input byte array as immutable when sending the message.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.Message : System.IO.Stream -&gt; Microsoft.Azure.Devices.Client.Message" Usage="new Microsoft.Azure.Devices.Client.Message stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="08f9b-106">本文ストリームとして使用されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="08f9b-106">a stream which will be used as body stream.</span></span></param>
        <summary>
            <span data-ttu-id="08f9b-107">本文ストリームとして引数のストリームを使用するコンス トラクターです。</span><span class="sxs-lookup"><span data-stu-id="08f9b-107">Constructor which uses the argument stream as the body stream.</span></span>
            </summary>
        <remarks><span data-ttu-id="08f9b-108">ユーザーは、このコンス トラクターを使用する場合に、ストリームの破棄を所有すると想定されます。</span><span class="sxs-lookup"><span data-stu-id="08f9b-108">User is expected to own the disposing of the stream when using this constructor.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream BodyStream { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IO.Stream BodyStream" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.BodyStream" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BodyStream As Stream" />
      <MemberSignature Language="F#" Value="member this.BodyStream : System.IO.Stream" Usage="Microsoft.Azure.Devices.Client.Message.BodyStream" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-109">コンテンツのエンコードのメッセージの種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-109">Used to specify the content encoding type of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-110">メッセージのコンテンツの種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-110">Used to specify the content type of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-111">メッセージの返信およびフィードバックの使用</span><span class="sxs-lookup"><span data-stu-id="08f9b-111">Used in message responses and feedback</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime CreationTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.CreationTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.Devices.Client.Message.CreationTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-112">カスタムの日付プロパティがメッセージの発信者によって設定します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-112">Custom date property set by the originator of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public uint DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As UInteger" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : uint32" Usage="Microsoft.Azure.Devices.Client.Message.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-113">メッセージがサーバーによって受信された時刻</span><span class="sxs-lookup"><span data-stu-id="08f9b-113">Time when the message was received by the server</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="message.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-114">現在のイベント データ インスタンスを破棄します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-114">Dispose the current event data instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.Devices.Client.Message.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-115">メッセージがサーバーによって受信された時刻</span><span class="sxs-lookup"><span data-stu-id="08f9b-115">Time when the message was received by the server</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiryTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiryTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.ExpiryTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiryTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiryTimeUtc : DateTime" Usage="Microsoft.Azure.Devices.Client.Message.ExpiryTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-116">[オプション]このメッセージを考慮する場合、時刻の有効期限が切れてください。</span><span class="sxs-lookup"><span data-stu-id="08f9b-116">[Optional] The time when this message is considered expired</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="message.GetBodyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-117">現在のイベント データ インスタンスの本文ストリームを返す</span><span class="sxs-lookup"><span data-stu-id="08f9b-117">Return the body stream of the current event data instance</span></span>
            </summary>
        <returns />
        <remarks><span data-ttu-id="08f9b-118">このメソッドは、1 回のみ呼び出すことができ、メソッドはスロー後<see cref="T:System.InvalidOperationException" />です。</span><span class="sxs-lookup"><span data-stu-id="08f9b-118">This method can only be called once and afterwards method will throw <see cref="T:System.InvalidOperationException" />.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="08f9b-119">メソッドが呼び出された場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="08f9b-119">throws if the method has been called.</span></span></exception>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="08f9b-120">イベント データは既に破棄されている場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="08f9b-120">throws if the event data has already been disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.Message.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="message.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-121">このメソッドは、バイト配列として本文ストリームを返す</span><span class="sxs-lookup"><span data-stu-id="08f9b-121">This methods return the body stream as a byte array</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="08f9b-122">イベント データは既に破棄されている場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="08f9b-122">throws if the event data has already been disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.Devices.Client.Message.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-123">[必須]受信したメッセージの LockToken</span><span class="sxs-lookup"><span data-stu-id="08f9b-123">[Required] LockToken of the received message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-124">[方法の 2 つの要求に必要]双方向通信を関連付けるために使用します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-124">[Required for two way requests] Used to correlate two-way communication.</span></span> <span data-ttu-id="08f9b-125">形式: 文字列 (最大 128 文字長) ASCII 7 ビットの英数字文字を使用</span><span class="sxs-lookup"><span data-stu-id="08f9b-125">Format: A case-sensitive string ( up to 128 char long) of ASCII 7-bit alphanumeric chars</span></span> 
            + <span data-ttu-id="08f9b-126">{'-', ':', '/', '\', '.', '+', '%', '_', '#', '\*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}.</span><span class="sxs-lookup"><span data-stu-id="08f9b-126">{'-', ':', '/', '\', '.', '+', '%', '_', '#', '\*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}.</span></span> <span data-ttu-id="08f9b-127">URN の RFC は英数字以外の文字です。</span><span class="sxs-lookup"><span data-stu-id="08f9b-127">Non-alphanumeric characters are from URN RFC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSchema">
      <MemberSignature Language="C#" Value="public string MessageSchema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.MessageSchema" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageSchema As String" />
      <MemberSignature Language="F#" Value="member this.MessageSchema : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.MessageSchema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-128">メッセージの内容のスキーマを指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-128">Used to specify the schema of the message content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Devices.Client.IReadOnlyIndicator.IsReadOnly">
      <MemberSignature Language="C#" Value="bool Microsoft.Azure.Devices.Client.IReadOnlyIndicator.IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Microsoft.Azure.Devices.Client.IReadOnlyIndicator.IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.Microsoft#Azure#Devices#Client#IReadOnlyIndicator#IsReadOnly" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property IsReadOnly As Boolean Implements IReadOnlyIndicator.IsReadOnly" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Client.Message.Microsoft.Azure.Devices.Client.IReadOnlyIndicator.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Devices.Client.IReadOnlyIndicator.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Devices.Client.Message.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-129">ディクショナリを取得時に設定されているユーザーのプロパティのユーザーがデータを送信します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-129">Gets the dictionary of user properties which are set when user send the data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public ulong SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As ULong" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : uint64" Usage="Microsoft.Azure.Devices.Client.Message.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.UInt64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-130">[必須]受信したメッセージのシーケンス番号</span><span class="sxs-lookup"><span data-stu-id="08f9b-130">[Required] SequenceNumber of the received message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-131">[必須]メッセージの送信先</span><span class="sxs-lookup"><span data-stu-id="08f9b-131">[Required] Destination of the message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.Message.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Devices.Client.Message.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08f9b-132">[フィードバック メッセージで必須]デバイスのハブによって生成されたメッセージの配信元を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="08f9b-132">[Required in feedback messages] Used to specify the origin of messages generated by device hub.</span></span> <span data-ttu-id="08f9b-133">使用可能な値:"{ハブ名}/"</span><span class="sxs-lookup"><span data-stu-id="08f9b-133">Possible value: “{hub name}/”</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>