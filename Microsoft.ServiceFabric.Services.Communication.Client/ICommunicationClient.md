<Type Name="ICommunicationClient" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient">
  <TypeSignature Language="C#" Value="public interface ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationClient" />
  <TypeSignature Language="F#" Value="type ICommunicationClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e3ed-101">信頼性の高いサービスの通信のクライアントを表すインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="1e3ed-101">Defines the interface that represents the communication client for reliable services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServiceEndpoint Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServiceEndpoint Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As ResolvedServiceEndpoint" />
      <MemberSignature Language="F#" Value="member this.Endpoint : System.Fabric.ResolvedServiceEndpoint with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServiceEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e3ed-102">取得または設定に、クライアントが接続されているサービス エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1e3ed-102">Gets or Sets the service endpoint to which the client is connected to.</span></span>
            </summary>
        <value>
          <see cref="T:System.Fabric.ResolvedServiceEndpoint" />
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ListenerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e3ed-103">取得またはレプリカまたはインスタンスに、クライアントが接続されているリスナーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1e3ed-103">Gets or Sets the name of the listener in the replica or instance to which the client is connected to.</span></span>
            </summary>
        <value><span data-ttu-id="1e3ed-104">リスナーの名前</span><span class="sxs-lookup"><span data-stu-id="1e3ed-104">Name of the listener</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedServicePartition">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition ResolvedServicePartition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition ResolvedServicePartition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolvedServicePartition As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.ResolvedServicePartition : System.Fabric.ResolvedServicePartition with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient.ResolvedServicePartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e3ed-105">取得または、このクライアントが作成されたときに使用された解決済みのサービス パーティションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e3ed-105">Gets or Sets the Resolved service partition which was used when this client was created.</span></span>
            </summary>
        <value>
          <span data-ttu-id="1e3ed-106"><see cref="T:System.Fabric.ResolvedServicePartition" /> オブジェクト</span><span class="sxs-lookup"><span data-stu-id="1e3ed-106"><see cref="T:System.Fabric.ResolvedServicePartition" /> object</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>