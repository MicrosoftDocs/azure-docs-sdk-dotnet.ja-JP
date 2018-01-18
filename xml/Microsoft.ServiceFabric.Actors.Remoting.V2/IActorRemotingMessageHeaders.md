<Type Name="IActorRemotingMessageHeaders" FullName="Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders">
  <TypeSignature Language="C#" Value="public interface IActorRemotingMessageHeaders : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorRemotingMessageHeaders implements class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorRemotingMessageHeaders&#xA;Implements IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="F#" Value="type IActorRemotingMessageHeaders = interface&#xA;    interface IServiceRemotingRequestMessageHeader" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="fa305-101">ServiceRemoting メッセージと共に送信されるヘッダーを指定します。</span><span class="sxs-lookup"><span data-stu-id="fa305-101">Specifies the headers that are sent along with a ServiceRemoting message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders.ActorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa305-102">これをリモート処理を要求をディスパッチは actorId です。</span><span class="sxs-lookup"><span data-stu-id="fa305-102">This is the actorId to which remoting request will dispatch to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CallContext">
      <MemberSignature Language="C#" Value="public string CallContext { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CallContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders.CallContext" />
      <MemberSignature Language="VB.NET" Value="Public Property CallContext As String" />
      <MemberSignature Language="F#" Value="member this.CallContext : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Remoting.V2.IActorRemotingMessageHeaders.CallContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa305-103">これを使用して、アクターに ren-entrancy を制限できます。</span><span class="sxs-lookup"><span data-stu-id="fa305-103">This is used to limit ren-entrancy in Actors.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>