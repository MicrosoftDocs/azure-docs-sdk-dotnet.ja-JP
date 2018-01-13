<Type Name="IServiceRemotingCallbackClient" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingCallbackClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingCallbackClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingCallbackClient" />
  <TypeSignature Language="F#" Value="type IServiceRemotingCallbackClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            クライアントにリモート処理リスナーからのコールバック機構を提供するために実装する必要があります、インターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OneWayMessage">
      <MemberSignature Language="C#" Value="public void OneWayMessage (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OneWayMessage(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient.OneWayMessage(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub OneWayMessage (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member OneWayMessage : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingCallbackClient.OneWayMessage (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders">メッセージ ヘッダー。</param>
        <param name="requestBody">メッセージの本文。</param>
        <summary>
            一方向のメッセージをクライアントに送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.IServiceRemotingCallbackClient.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingCallbackClient.RequestResponseAsync (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders">メッセージ ヘッダー。</param>
        <param name="requestBody">メッセージの本文。</param>
        <summary>
            クライアントにメッセージを送信し、応答を取得します。
            </summary>
        <returns>応答本文</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>