<Type Name="IServiceRemotingMessageHandler" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リモート処理トランスポートからメッセージを受信する ServiceRemotingListener で実装する必要があります、インターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetRemotingMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.GetRemotingMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemotingMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="iServiceRemotingMessageHandler.GetRemotingMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            IServiceRemotingMessageBodyFactory を返します。 リモート処理応答の本文を作成するディスパッチャーによって使用されます。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleOneWayMessage">
      <MemberSignature Language="C#" Value="public void HandleOneWayMessage (Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void HandleOneWayMessage(class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.HandleOneWayMessage(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub HandleOneWayMessage (requestMessage As IServiceRemotingRequestMessage)" />
      <MemberSignature Language="F#" Value="abstract member HandleOneWayMessage : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; unit" Usage="iServiceRemotingMessageHandler.HandleOneWayMessage requestMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestMessage" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage" />
      </Parameters>
      <Docs>
        <param name="requestMessage">要求メッセージ</param>
        <summary>
            クライアントから一方向のメッセージを処理します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleRequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.HandleRequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function HandleRequestResponseAsync (requestContext As IServiceRemotingRequestContext, requestMessage As IServiceRemotingRequestMessage) As Task(Of IServiceRemotingResponseMessage)" />
      <MemberSignature Language="F#" Value="abstract member HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;" Usage="iServiceRemotingMessageHandler.HandleRequestResponseAsync (requestContext, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="requestMessage" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage" />
      </Parameters>
      <Docs>
        <param name="requestContext">要求に関する追加情報が含まれています。</param>
        <param name="requestMessage">要求メッセージ。</param>
        <summary>
            サービスからの応答を必要とするクライアントからのメッセージを処理します。
            </summary>
        <returns>応答本文です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>