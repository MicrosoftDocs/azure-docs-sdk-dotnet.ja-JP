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
    <summary>コンテンツのストリーミングから、メッセージ オブジェクトを作成するためのヘルパー クラス。</summary>
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
        <param name="version"> メッセージのバージョン。</param>
        <param name="action"> メッセージの処理方法の説明。</param>
        <param name="jsonStream"> 新しいメッセージの本文の書き込みに使用されるコンテンツを含んでいるストリーム。</param>
        <summary>JSON メッセージを指定したバージョンを作成します。</summary>
        <returns>作成された JSON メッセージ。</returns>
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
        <param name="version"> 新しく作成されたメッセージに使用するアドレス指定とエンベロープ バージョンを指定します。 REST を使用して、要求が行われる場合、アドレス指定とエンベロープのバージョンは None です。</param>
        <param name="action"> メッセージの処理方法の説明。 HTTP 要求に対する応答で送信されるメッセージでは、この値は"GETRESPONSE"をする必要があります。</param>
        <param name="writer"> 許可するデリゲート<see cref="M:Microsoft.ServiceBus.Web.StreamMessageHelper.CreateMessage" />コールバックし、メッセージの本文を設定するストリームを要求します。</param>
        <summary>指定したバージョン、アクション、およびデリゲートを使用して、ストリームからメッセージを作成します。</summary>
        <returns>ストリームが作成したを返します<see cref="T:System.ServiceModel.Channels.Message" />です。</returns>
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
        <param name="version"> 新しく作成されたメッセージに使用するアドレス指定とエンベロープ バージョンを指定します。 REST を使用して、要求が行われる場合、アドレス指定とエンベロープのバージョンは None です。</param>
        <param name="action"> メッセージの処理方法の説明。 HTTP 要求に対する応答で送信されるメッセージでは、この値は"GETRESPONSE"をする必要があります。</param>
        <param name="stream"> 新しいメッセージの本文の書き込みに使用されるコンテンツを含んでいるストリーム。</param>
        <summary>指定したバージョン、アクション、およびストリームを使用して、メッセージを作成します。</summary>
        <returns>ストリームが作成したを返します<see cref="T:System.ServiceModel.Channels.Message" />です。</returns>
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
        <param name="message"> メッセージ。</param>
        <summary>指定されたメッセージのストリームを取得します。</summary>
        <returns>返します、<see cref="T:System.IO.Stream" />メッセージのストリームを格納しています。 ストリームは常に、メッセージ本文が空かどうかに関係なく返されます。</returns>
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
        <param name="reader"> リーダー。</param>
        <summary>指定したリーダーで指定されたメッセージのストリームを取得します。</summary>
        <returns>指定されたメッセージのストリーム。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>