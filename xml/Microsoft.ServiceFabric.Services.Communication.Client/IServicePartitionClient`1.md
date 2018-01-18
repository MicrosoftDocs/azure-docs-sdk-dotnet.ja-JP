<Type Name="IServicePartitionClient&lt;TCommunicationClient&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;TCommunicationClient&gt;">
  <TypeSignature Language="C#" Value="public interface IServicePartitionClient&lt;TCommunicationClient&gt; where TCommunicationClient : ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartitionClient`1&lt;(class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient) TCommunicationClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartitionClient(Of TCommunicationClient)" />
  <TypeSignature Language="F#" Value="type IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; ICommunicationClient)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TCommunicationClient">
      <Constraints>
        <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="TCommunicationClient"><span data-ttu-id="79e2d-101">ICommunicationClient の種類</span><span class="sxs-lookup"><span data-stu-id="79e2d-101">Type of ICommunicationClient</span></span></typeparam>
    <summary>
            <span data-ttu-id="79e2d-102">特定のサービス パーティションのレプリカと通信できるクライアントのインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-102">Defines the interface for the client that can communicate with replicas of a particular service partition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Factory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt; Factory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory`1&lt;!TCommunicationClient&gt; Factory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.Factory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Factory As ICommunicationClientFactory(Of TCommunicationClient)" />
      <MemberSignature Language="F#" Value="member this.Factory : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.Factory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClientFactory&lt;TCommunicationClient&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79e2d-103">通信のクライアントのファクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-103">Gets the communication client factory</span></span>
            </summary>
        <value><span data-ttu-id="79e2d-104">クライアント ファクトリは通信</span><span class="sxs-lookup"><span data-stu-id="79e2d-104">Communication client factory</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ListenerName" />
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
            <span data-ttu-id="79e2d-105">レプリカにクライアントが接続するには、リスナーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-105">Gets the name of the listener in the replica to which the client should connect to.</span></span>
            </summary>
        <value><span data-ttu-id="79e2d-106">リスナー名</span><span class="sxs-lookup"><span data-stu-id="79e2d-106">Listener name</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As ServicePartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" Usage="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79e2d-107">クライアントが通信して、パーティションのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-107">Gets the key of the partition the client is communicating with.</span></span> 
            </summary>
        <value><span data-ttu-id="79e2d-108">パーティション キー</span><span class="sxs-lookup"><span data-stu-id="79e2d-108">Partition key</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri" Usage="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79e2d-109">サービスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-109">Gets the name of the service</span></span>
            </summary>
        <value><span data-ttu-id="79e2d-110">サービスの名前</span><span class="sxs-lookup"><span data-stu-id="79e2d-110">Name of the service</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSelector">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector TargetReplicaSelector" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TargetReplicaSelector" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplicaSelector As TargetReplicaSelector" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSelector : Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" Usage="Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient&lt;'CommunicationClient (requires 'CommunicationClient :&gt; Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient)&gt;.TargetReplicaSelector" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79e2d-111">パーティションのレプリカは、クライアントが接続する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-111">Gets the information about which replica in the partition the client should connect to.</span></span>
            </summary>
        <value><span data-ttu-id="79e2d-112"><see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />。</span><span class="sxs-lookup"><span data-stu-id="79e2d-112">A <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" /></span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetLastResolvedServicePartition">
      <MemberSignature Language="C#" Value="public bool TryGetLastResolvedServicePartition (out System.Fabric.ResolvedServicePartition resolvedServicePartition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetLastResolvedServicePartition([out] class System.Fabric.ResolvedServicePartition&amp; resolvedServicePartition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.IServicePartitionClient`1.TryGetLastResolvedServicePartition(System.Fabric.ResolvedServicePartition@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetLastResolvedServicePartition (ByRef resolvedServicePartition As ResolvedServicePartition) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetLastResolvedServicePartition :  -&gt; bool" Usage="iServicePartitionClient.TryGetLastResolvedServicePartition resolvedServicePartition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resolvedServicePartition" Type="System.Fabric.ResolvedServicePartition&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="resolvedServicePartition"><span data-ttu-id="79e2d-113">以前の ResolvedServicePartition</span><span class="sxs-lookup"><span data-stu-id="79e2d-113">previous ResolvedServicePartition</span></span></param>
        <summary>
            <span data-ttu-id="79e2d-114">クライアントで設定された解決済みのサービス パーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="79e2d-114">Gets the resolved service partition that was set on the client.</span></span>
            </summary>
        <returns><span data-ttu-id="79e2d-115">ResolvedServicePartition 場合は true が設定されました</span><span class="sxs-lookup"><span data-stu-id="79e2d-115">true if a ResolvedServicePartition was set</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>