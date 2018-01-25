<Type Name="MessageInteropExtensions" FullName="Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions">
  <TypeSignature Language="C#" Value="public static class MessageInteropExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MessageInteropExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MessageInteropExtensions" />
  <TypeSignature Language="F#" Value="type MessageInteropExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="07952-101">WindowsAzure.Messaging クライアント ライブラリを使用してシリアル化され、ServiceBus キュー/トピックに送信されたメッセージの本文を逆シリアル化する拡張メソッドを提供するメッセージ拡張クラス。</span><span class="sxs-lookup"><span data-stu-id="07952-101">A Message Extension Class that provides extension methods to deserialize the body of a message that was serialized and sent to ServiceBus Queue/Topic using the WindowsAzure.Messaging client library.</span></span> <span data-ttu-id="07952-102">WindowsAzure.Messaging クライアント ライブラリを使用してオブジェクトをシリアル化、 <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> (既定のシリアライザー) または<see cref="T:System.Runtime.Serialization.DataContractSerializer" />メッセージを送信するときにします。</span><span class="sxs-lookup"><span data-stu-id="07952-102">The WindowsAzure.Messaging client library serializes objects using the <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> (default serializer) or <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> when sending message.</span></span> <span data-ttu-id="07952-103">このクラスは、逆シリアル化し、このようなメッセージの本文を取得する拡張メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="07952-103">This class provides extension methods to deserialize and retrieve the body of such messages.</span></span>
             </summary>
    <remarks>
             1. <span data-ttu-id="07952-104">メッセージが送信されるだけこの Microsoft.Azure.ServiceBus クライアント ライブラリを使用して受信した場合、拡張機能の下のメソッドは不適切でありは使用できません。</span><span class="sxs-lookup"><span data-stu-id="07952-104">If a message is only being sent and received using this Microsoft.Azure.ServiceBus client library, then the below extension methods are not relevant and should not be used.</span></span>
             
            2. <span data-ttu-id="07952-105">このクライアント ライブラリが WindowsAzure.Messaging クライアント ライブラリと、この (Microsoft.Azure.ServiceBus) ライブラリの両方を使用して送信されたメッセージを受信するために使用するかどうかは、ユーザーは、ユーザー プロパティを追加する必要があります<see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />メッセージを送信中にします。</span><span class="sxs-lookup"><span data-stu-id="07952-105">If this client library will be used to receive messages that were sent using both WindowsAzure.Messaging client library and this (Microsoft.Azure.ServiceBus) library, then the Users need to add a User property <see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" /> while sending the message.</span></span> <span data-ttu-id="07952-106">メッセージを受け取ると、このプロパティは、WindowsAzure.Messaging クライアント ライブラリからメッセージがかどうかを確認して、その場合は、メッセージを使用して調べることができます。メッセージに関連付けられている実際の本文を取得する GetBody() 拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="07952-106">On receiving the message, this property can be examined to determine if the message was from WindowsAzure.Messaging client library and if so use the message.GetBody() extension method to get the actual body associated with the message.</span></span>
             
             ----------------------------------------------
             <a name="scenarios-to-use-the-getbody-extension-method"></a><span data-ttu-id="07952-107">GetBody 拡張メソッドを使用するシナリオ。</span><span class="sxs-lookup"><span data-stu-id="07952-107">Scenarios to use the GetBody Extension method:</span></span>
             ----------------------------------------------
             <span data-ttu-id="07952-108">メッセージは、次のように、WindowsAzure.Messaging クライアント ライブラリを使用して構成されました。 場合、</span><span class="sxs-lookup"><span data-stu-id="07952-108">If message was constructed using the WindowsAzure.Messaging client library as follows:</span></span>
             <code>
            var message1 = new BrokeredMessage("contoso"); // Sending a plain string
             var message2 = new BrokeredMessage(sampleObject); // Sending an actual customer object
             var message3 = new BrokeredMessage(Encoding.UTF8.GetBytes("contoso")); // Sending a UTF8 encoded byte array object
             
             await messageSender.SendAsync(message1);
             await messageSender.SendAsync(message2);
                 await messageSender.SendAsync(message3);
                 </code>
                 
            <span data-ttu-id="07952-109">次のように、このクライアント ライブラリを使用して元のオブジェクトを取得: (既定では<see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" />を逆シリアル化および本文を取得するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="07952-109">Then retrieve the original objects using this client library as follows: (By default <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> will be used to deserialize and retrieve the body.</span></span>
                 <span data-ttu-id="07952-110">シリアライザーが使用したもの以外で場合、シリアライザーで明示的に渡す。)</span><span class="sxs-lookup"><span data-stu-id="07952-110">If a serializer other than that was used, pass in the serializer explicitly.)</span></span>
                 <code>
                 var message1 = await messageReceiver.ReceiveAsync();
             var returnedData1 = message1.GetBody&lt;string&gt;();
            
             var message2 = await messageReceiver.ReceiveAsync();
             var returnedData2 = message1.GetBody&lt;SampleObject&gt;();
              
             var message3 = await messageReceiver.ReceiveAsync();
                 var returnedData3Bytes = message1.GetBody&lt;byte[]&gt;();
                 Console.WriteLine($"Message3 String: {Encoding.UTF8.GetString(returnedData3Bytes)}");
            </code>
                 
                 -------------------------------------------------
            <a name="scenarios-to-not-use-the-getbody-extension-method"></a><span data-ttu-id="07952-111">GetBody 拡張メソッドを使用するシナリオ。</span><span class="sxs-lookup"><span data-stu-id="07952-111">Scenarios to NOT use the GetBody Extension method:</span></span>
                 -------------------------------------------------
                 <span data-ttu-id="07952-112">次のように WindowsAzure.Messaging クライアント ライブラリを使ってメッセージを送信したかどうか: var message4 = 新しい BrokeredMessage (新しい MemoryStream(Encoding.UTF8.GetBytes("contoso"))) です。await messageSender.SendAsync(message4) です。</span><span class="sxs-lookup"><span data-stu-id="07952-112">If message was sent using the WindowsAzure.Messaging client library as follows: var message4 = new BrokeredMessage(new MemoryStream(Encoding.UTF8.GetBytes("contoso"))); await messageSender.SendAsync(message4);</span></span>
                 
             <span data-ttu-id="07952-113">次のように、このクライアント ライブラリを使用して元のオブジェクトを取得します。 var message4 = await messageReceiver.ReceiveAsync() です。返される文字列 = Encoding.UTF8.GetString (message4 です。本文) です。ここで必要のないの逆シリアル化ストリームとしてメッセージが送信されました。</span><span class="sxs-lookup"><span data-stu-id="07952-113">Then retrieve the original objects using this client library as follows: var message4 = await messageReceiver.ReceiveAsync(); string returned = Encoding.UTF8.GetString(message4.Body); // Since message was sent as Stream, no deserialization required here.</span></span>
            
             </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T GetBody&lt;T&gt; (this Microsoft.Azure.ServiceBus.Message message, System.Runtime.Serialization.XmlObjectSerializer serializer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T GetBody&lt;T&gt;(class Microsoft.Azure.ServiceBus.Message message, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions.GetBody``1(Microsoft.Azure.ServiceBus.Message,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="static member GetBody : Microsoft.Azure.ServiceBus.Message * System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions.GetBody (message, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" RefType="this" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="message">To be added.</param>
        <param name="serializer">To be added.</param>
        <summary>
            <span data-ttu-id="07952-114">XmlObjectSerializer を使用してシリアル化されたメッセージの本文を逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="07952-114">Deserializes the body of a message that was serialized using XmlObjectSerializer</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>