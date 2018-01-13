<Type Name="IActorProxy" FullName="Microsoft.ServiceFabric.Actors.Client.IActorProxy">
  <TypeSignature Language="C#" Value="public interface IActorProxy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorProxy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorProxy" />
  <TypeSignature Language="F#" Value="type IActorProxy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45479-101">アクター サービスに対するプロキシ アクセスを実装するため、インターフェイスを提供します。</span><span class="sxs-lookup"><span data-stu-id="45479-101">Provides the interface for implementation of proxy access for actor service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorId" />
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
            <span data-ttu-id="45479-102">取得<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="45479-102">Gets <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span>
            </summary>
        <value>
          <span data-ttu-id="45479-103"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />プロキシ オブジェクトに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="45479-103"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> associated with the proxy object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient ActorServicePartitionClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClient As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClient : Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45479-104">取得<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しています。</span><span class="sxs-lookup"><span data-stu-id="45479-104">Gets <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="45479-105"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</span><span class="sxs-lookup"><span data-stu-id="45479-105"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorServicePartitionClientV2">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient ActorServicePartitionClientV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorServicePartitionClientV2 As IActorServicePartitionClient" />
      <MemberSignature Language="F#" Value="member this.ActorServicePartitionClientV2 : Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" Usage="Microsoft.ServiceFabric.Actors.Client.IActorProxy.ActorServicePartitionClientV2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45479-106">取得<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />アクターとの通信にこのプロキシを使用しています。</span><span class="sxs-lookup"><span data-stu-id="45479-106">Gets <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="45479-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" />このプロキシが使用しているアクターと通信します。</span><span class="sxs-lookup"><span data-stu-id="45479-107"><see cref="T:Microsoft.ServiceFabric.Actors.Remoting.V2.Client.IActorServicePartitionClient" /> that this proxy is using to communicate with the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>