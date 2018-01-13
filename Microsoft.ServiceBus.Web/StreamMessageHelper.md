<Type Name="StreamMessageHelper" FullName="Microsoft.ServiceBus.Web.StreamMessageHelper">
  <TypeSignature Language="C#" Value="public static class StreamMessageHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamMessageHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Web.StreamMessageHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamMessageHelper" />
  <TypeSignature Language="F#" Value="type StreamMessageHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="046a8-101">コンテンツのストリーミングから、メッセージ オブジェクトを作成するためのヘルパー クラス。</span><span class="sxs-lookup"><span data-stu-id="046a8-101">Helper class for creating a Message object from streaming content.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateJsonMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateJsonMessage (System.ServiceModel.Channels.MessageVersion version, string action, System.IO.Stream jsonStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateJsonMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class System.IO.Stream jsonStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateJsonMessage(System.ServiceModel.Channels.MessageVersion,System.String,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateJsonMessage (version As MessageVersion, action As String, jsonStream As Stream) As Message" />
      <MemberSignature Language="F#" Value="static member CreateJsonMessage : System.ServiceModel.Channels.MessageVersion * string * System.IO.Stream -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateJsonMessage (version, action, jsonStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="jsonStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="046a8-102">メッセージのバージョン。</span><span class="sxs-lookup"><span data-stu-id="046a8-102">The message version.</span></span></param>
        <param name="action"> <span data-ttu-id="046a8-103">メッセージの処理方法の説明。</span><span class="sxs-lookup"><span data-stu-id="046a8-103">A description of how the message should be processed.</span></span></param>
        <param name="jsonStream"> <span data-ttu-id="046a8-104">新しいメッセージの本文の書き込みに使用されるコンテンツを含んでいるストリーム。</span><span class="sxs-lookup"><span data-stu-id="046a8-104">A stream that contains content used to write the body of the new message.</span></span></param>
        <summary><span data-ttu-id="046a8-105">JSON メッセージを指定したバージョンを作成します。</span><span class="sxs-lookup"><span data-stu-id="046a8-105">Creates a JSON message with a specified version.</span></span></summary>
        <returns><span data-ttu-id="046a8-106">作成された JSON メッセージ。</span><span class="sxs-lookup"><span data-stu-id="046a8-106">The created JSON message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateMessage (System.ServiceModel.Channels.MessageVersion version, string action, Microsoft.ServiceBus.Web.StreamWriterDelegate writer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class Microsoft.ServiceBus.Web.StreamWriterDelegate writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage(System.ServiceModel.Channels.MessageVersion,System.String,Microsoft.ServiceBus.Web.StreamWriterDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateMessage (version As MessageVersion, action As String, writer As StreamWriterDelegate) As Message" />
      <MemberSignature Language="F#" Value="static member CreateMessage : System.ServiceModel.Channels.MessageVersion * string * Microsoft.ServiceBus.Web.StreamWriterDelegate -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage (version, action, writer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="writer" Type="Microsoft.ServiceBus.Web.StreamWriterDelegate" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="046a8-107">新しく作成されたメッセージに使用するアドレス指定とエンベロープ バージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="046a8-107">Specifies the addressing and envelope versions to use for the newly created message.</span></span> <span data-ttu-id="046a8-108">REST を使用して、要求が行われる場合、アドレス指定とエンベロープのバージョンは None です。</span><span class="sxs-lookup"><span data-stu-id="046a8-108">If the request is made using REST, the Addressing and Envelope version are None.</span></span></param>
        <param name="action"> <span data-ttu-id="046a8-109">メッセージの処理方法の説明。</span><span class="sxs-lookup"><span data-stu-id="046a8-109">A description of how the message should be processed.</span></span> <span data-ttu-id="046a8-110">HTTP 要求に対する応答で送信されるメッセージでは、この値は"GETRESPONSE"をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="046a8-110">For messages sent in response to a HTTP request, this value must be “GETRESPONSE”.</span></span></param>
        <param name="writer"> <span data-ttu-id="046a8-111">許可するデリゲート<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" />コールバックし、メッセージの本文を設定するストリームを要求します。</span><span class="sxs-lookup"><span data-stu-id="046a8-111">A delegate that allows<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" /> to call back and ask for a Stream to populate the body of the message.</span></span></param>
        <summary><span data-ttu-id="046a8-112">指定したバージョン、アクション、およびデリゲートを使用して、ストリームからメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="046a8-112">Creates a message from a stream, using the specified version, action, and delegate.</span></span></summary>
        <returns><span data-ttu-id="046a8-113">ストリームが作成したを返します<see cref="T:System.ServiceModel.Channels.Message" />です。</span><span class="sxs-lookup"><span data-stu-id="046a8-113">Returns a stream-created<see cref="T:System.ServiceModel.Channels.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessage">
      <MemberSignature Language="C#" Value="public static System.ServiceModel.Channels.Message CreateMessage (System.ServiceModel.Channels.MessageVersion version, string action, System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.ServiceModel.Channels.Message CreateMessage(class System.ServiceModel.Channels.MessageVersion version, string action, class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage(System.ServiceModel.Channels.MessageVersion,System.String,System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member CreateMessage : System.ServiceModel.Channels.MessageVersion * string * System.IO.Stream -&gt; System.ServiceModel.Channels.Message" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage (version, action, stream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.Message</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.ServiceModel.Channels.MessageVersion" />
        <Parameter Name="action" Type="System.String" />
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="version"> <span data-ttu-id="046a8-114">新しく作成されたメッセージに使用するアドレス指定とエンベロープ バージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="046a8-114">Specifies the addressing and envelope versions to use for the newly created message.</span></span> <span data-ttu-id="046a8-115">REST を使用して、要求が行われる場合、アドレス指定とエンベロープのバージョンは None です。</span><span class="sxs-lookup"><span data-stu-id="046a8-115">If the request is made using REST, the Addressing and Envelope version are None.</span></span></param>
        <param name="action"> <span data-ttu-id="046a8-116">メッセージの処理方法の説明。</span><span class="sxs-lookup"><span data-stu-id="046a8-116">A description of how the message should be processed.</span></span> <span data-ttu-id="046a8-117">HTTP 要求に対する応答で送信されるメッセージでは、この値は"GETRESPONSE"をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="046a8-117">For messages sent in response to a HTTP request, this value must be “GETRESPONSE”.</span></span></param>
        <param name="stream"> <span data-ttu-id="046a8-118">新しいメッセージの本文の書き込みに使用されるコンテンツを含んでいるストリーム。</span><span class="sxs-lookup"><span data-stu-id="046a8-118">A stream that contains content used to write the body of the new message.</span></span></param>
        <summary><span data-ttu-id="046a8-119">指定したバージョン、アクション、およびストリームを使用して、メッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="046a8-119">Creates a message, using the specified version, action, and stream.</span></span></summary>
        <returns><span data-ttu-id="046a8-120">ストリームが作成したを返します<see cref="T:System.ServiceModel.Channels.Message" />です。</span><span class="sxs-lookup"><span data-stu-id="046a8-120">Returns a stream-created<see cref="T:System.ServiceModel.Channels.Message" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStream">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetStream (System.ServiceModel.Channels.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetStream(class System.ServiceModel.Channels.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream(System.ServiceModel.Channels.Message)" />
      <MemberSignature Language="F#" Value="static member GetStream : System.ServiceModel.Channels.Message -&gt; System.IO.Stream" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.ServiceModel.Channels.Message" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="046a8-121">メッセージ。</span><span class="sxs-lookup"><span data-stu-id="046a8-121">The message.</span></span></param>
        <summary><span data-ttu-id="046a8-122">指定されたメッセージのストリームを取得します。</span><span class="sxs-lookup"><span data-stu-id="046a8-122">Retrieves the stream of the specified message.</span></span></summary>
        <returns><span data-ttu-id="046a8-123">返します、<see cref="T:System.IO.Stream" />メッセージのストリームを格納しています。</span><span class="sxs-lookup"><span data-stu-id="046a8-123">Returns a<see cref="T:System.IO.Stream" /> that contains the stream of the message.</span></span> <span data-ttu-id="046a8-124">ストリームは常に、メッセージ本文が空かどうかに関係なく返されます。</span><span class="sxs-lookup"><span data-stu-id="046a8-124">A Stream is always returned regardless of whether the message body is empty.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStream">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetStream (System.Xml.XmlDictionaryReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetStream(class System.Xml.XmlDictionaryReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream(System.Xml.XmlDictionaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetStream (reader As XmlDictionaryReader) As Stream" />
      <MemberSignature Language="F#" Value="static member GetStream : System.Xml.XmlDictionaryReader -&gt; System.IO.Stream" Usage="Microsoft.ServiceBus.Web.StreamMessageHelper.GetStream reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlDictionaryReader" />
      </Parameters>
      <Docs>
        <param name="reader"> <span data-ttu-id="046a8-125">リーダー。</span><span class="sxs-lookup"><span data-stu-id="046a8-125">The reader.</span></span></param>
        <summary><span data-ttu-id="046a8-126">指定したリーダーで指定されたメッセージのストリームを取得します。</span><span class="sxs-lookup"><span data-stu-id="046a8-126">Retrieves the stream of the specified message with the specified reader.</span></span></summary>
        <returns><span data-ttu-id="046a8-127">指定されたメッセージのストリーム。</span><span class="sxs-lookup"><span data-stu-id="046a8-127">The stream of the specified message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>