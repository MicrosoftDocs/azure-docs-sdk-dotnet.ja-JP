<Type Name="IServiceRemotingCallbackClient" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingCallbackClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingCallbackClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingCallbackClient" />
  <TypeSignature Language="F#" Value="type IServiceRemotingCallbackClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e9fa4-101">クライアントにリモート処理リスナーからのコールバック機構を提供するために実装する必要があります、インターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="e9fa4-101">Defines the interface that must be implemented for providing callback mechanism from the remoting listener to the client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetRemotingMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient.GetRemotingMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemotingMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="iServiceRemotingCallbackClient.GetRemotingMessageBodyFactory " />
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
            <span data-ttu-id="e9fa4-102">IServiceRemotingMessageBodyFactory を返します。</span><span class="sxs-lookup"><span data-stu-id="e9fa4-102">Returns the IServiceRemotingMessageBodyFactory .</span></span> <span data-ttu-id="e9fa4-103">リモート処理を要求本文を作成する CallBackClient によって使用されます。</span><span class="sxs-lookup"><span data-stu-id="e9fa4-103">It is used by CallBackClient to create Remoting Request Body</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendOneWay">
      <MemberSignature Language="C#" Value="public void SendOneWay (Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendOneWay(class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingCallbackClient.SendOneWay(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendOneWay (requestMessage As IServiceRemotingRequestMessage)" />
      <MemberSignature Language="F#" Value="abstract member SendOneWay : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; unit" Usage="iServiceRemotingCallbackClient.SendOneWay requestMessage" />
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
        <param name="requestMessage"><span data-ttu-id="e9fa4-104">リモート処理の要求メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e9fa4-104">The remoting request message.</span></span></param>
        <summary>
            <span data-ttu-id="e9fa4-105">一方向のメッセージをクライアントに送信します。</span><span class="sxs-lookup"><span data-stu-id="e9fa4-105">Sends a one way message to the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>