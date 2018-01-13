<Type Name="IServiceRemotingRequestContext" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestContext" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestContext = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            インターフェイスを定義します、IServiceRemotingMessageHandler の要求コンテキストを指定するために実装する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCallBackClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient GetCallBackClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient GetCallBackClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext.GetCallBackClient" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCallBackClient () As IServiceRemotingCallbackClient" />
      <MemberSignature Language="F#" Value="abstract member GetCallBackClient : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient" Usage="iServiceRemotingRequestContext.GetCallBackClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービスがクライアントへの呼び出しを開始しようとした場所の場合に使用するクライアント チャネル インターフェイスを取得します。
            </summary>
        <returns>リモート処理のコールバック クライアント。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>