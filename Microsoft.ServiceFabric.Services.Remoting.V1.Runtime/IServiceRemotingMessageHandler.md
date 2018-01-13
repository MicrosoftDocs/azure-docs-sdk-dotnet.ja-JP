<Type Name="IServiceRemotingMessageHandler" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9b6f3-101">リモート処理トランスポートからメッセージを受信する ServiceRemotingListener で実装する必要があります、インターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-101">Defines the interface that must be implemented by the ServiceRemotingListener to receive messages from the remoting transport.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HandleOneWay">
      <MemberSignature Language="C#" Value="public void HandleOneWay (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void HandleOneWay(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.HandleOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub HandleOneWay (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member HandleOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingMessageHandler.HandleOneWay (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext"><span data-ttu-id="9b6f3-102">要求に関する追加情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-102">Contains additional information about the request.</span></span></param>
        <param name="messageHeaders"><span data-ttu-id="9b6f3-103">要求メッセージ ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-103">The request message headers.</span></span></param>
        <param name="requestBody"><span data-ttu-id="9b6f3-104">要求メッセージの本文。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-104">The request message body.</span></span></param>
        <summary>
            <span data-ttu-id="9b6f3-105">クライアントから一方向のメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-105">Handles a one way message from the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingMessageHandler.RequestResponseAsync (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext"><span data-ttu-id="9b6f3-106">要求に関する追加情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-106">Contains additional information about the request.</span></span></param>
        <param name="messageHeaders"><span data-ttu-id="9b6f3-107">要求メッセージ ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-107">The request message headers.</span></span></param>
        <param name="requestBody"><span data-ttu-id="9b6f3-108">要求メッセージの本文。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-108">The request message body.</span></span></param>
        <summary>
            <span data-ttu-id="9b6f3-109">サービスからの応答を必要とするクライアントからのメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-109">Handles a message from the client that requires a response from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="9b6f3-110">応答本文です。</span><span class="sxs-lookup"><span data-stu-id="9b6f3-110">The response body.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>