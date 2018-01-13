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
             WindowsAzure.Messaging クライアント ライブラリを使用してシリアル化され、ServiceBus キュー/トピックに送信されたメッセージの本文を逆シリアル化する拡張メソッドを提供するメッセージ拡張クラス。 WindowsAzure.Messaging クライアント ライブラリを使用してオブジェクトをシリアル化、 <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> (既定のシリアライザー) または<see cref="T:System.Runtime.Serialization.DataContractSerializer" />メッセージを送信するときにします。 このクラスは、逆シリアル化し、このようなメッセージの本文を取得する拡張メソッドを提供します。
             </summary>
    <remarks>
             1. メッセージが送信されるだけこの Microsoft.Azure.ServiceBus クライアント ライブラリを使用して受信した場合、拡張機能の下のメソッドは不適切でありは使用できません。
             
            2. このクライアント ライブラリが WindowsAzure.Messaging クライアント ライブラリと、この (Microsoft.Azure.ServiceBus) ライブラリの両方を使用して送信されたメッセージを受信するために使用するかどうかは、ユーザーは、ユーザー プロパティを追加する必要があります<see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" />メッセージを送信中にします。 メッセージを受け取ると、このプロパティは、WindowsAzure.Messaging クライアント ライブラリからメッセージがかどうかを確認して、その場合は、メッセージを使用して調べることができます。メッセージに関連付けられている実際の本文を取得する GetBody() 拡張メソッド。
             
             ----------------------------------------------
             <a name="scenarios-to-use-the-getbody-extension-method"></a>GetBody 拡張メソッドを使用するシナリオ。
             ----------------------------------------------
             メッセージは、次のように、WindowsAzure.Messaging クライアント ライブラリを使用して構成されました。 場合、
             <code>
            var message1 = new BrokeredMessage("contoso"); // Sending a plain string
             var message2 = new BrokeredMessage(sampleObject); // Sending an actual customer object
             var message3 = new BrokeredMessage(Encoding.UTF8.GetBytes("contoso")); // Sending a UTF8 encoded byte array object
             
             await messageSender.SendAsync(message1);
             await messageSender.SendAsync(message2);
                 await messageSender.SendAsync(message3);
                 </code>
                 
            次のように、このクライアント ライブラリを使用して元のオブジェクトを取得: (既定では<see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" />を逆シリアル化および本文を取得するために使用されます。
                 シリアライザーが使用したもの以外で場合、シリアライザーで明示的に渡す。)
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
            <a name="scenarios-to-not-use-the-getbody-extension-method"></a>GetBody 拡張メソッドを使用するシナリオ。
                 -------------------------------------------------
                 次のように WindowsAzure.Messaging クライアント ライブラリを使ってメッセージを送信したかどうか: var message4 = 新しい BrokeredMessage (新しい MemoryStream(Encoding.UTF8.GetBytes("contoso"))) です。await messageSender.SendAsync(message4) です。
                 
             次のように、このクライアント ライブラリを使用して元のオブジェクトを取得します。 var message4 = await messageReceiver.ReceiveAsync() です。返される文字列 = Encoding.UTF8.GetString (message4 です。本文) です。ここで必要のないの逆シリアル化ストリームとしてメッセージが送信されました。
            
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
            XmlObjectSerializer を使用してシリアル化されたメッセージの本文を逆シリアル化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>