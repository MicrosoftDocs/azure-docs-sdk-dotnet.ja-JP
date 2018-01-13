<Type Name="ServiceRemotingMessageDispatcher" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher">
  <TypeSignature Language="C#" Value="public class ServiceRemotingMessageDispatcher : IDisposable, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingMessageDispatcher extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingMessageDispatcher&#xA;Implements IDisposable, IServiceRemotingMessageHandler" />
  <TypeSignature Language="F#" Value="type ServiceRemotingMessageDispatcher = class&#xA;    interface IServiceRemotingMessageHandler&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="130e1-101">実装を提供<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />サービスの実装にメッセージをディスパッチする<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="130e1-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" /> that can dispatch messages to the service implementing <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingMessageDispatcher (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingMessageBodyFactory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingMessageBodyFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher (serviceContext, serviceImplementation, serviceRemotingMessageBodyFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="serviceRemotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="130e1-102">サービス コンテキスト</span><span class="sxs-lookup"><span data-stu-id="130e1-102">Service context</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="130e1-103">型のインターフェイスを実装するサービスの実装<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /></span><span class="sxs-lookup"><span data-stu-id="130e1-103">Service implementation that implements interfaces of type <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /></span></span></param>
        <param name="serviceRemotingMessageBodyFactory"><span data-ttu-id="130e1-104">これは、リモート処理の応答オブジェクトを作成するディスパッチャーによって使用されるファクトリ</span><span class="sxs-lookup"><span data-stu-id="130e1-104">This is the factory used by Dispatcher to create Remoting Response object</span></span></param>
        <summary>
            <span data-ttu-id="130e1-105">特定のサービス コンテキストを使用し、指定されたサービスの実装にメッセージをディスパッチ ServiceRemotingDispatcher をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="130e1-105">Instantiates the ServiceRemotingDispatcher that uses the given service context and dispatches messages to the given service implementation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingMessageDispatcher (System.Collections.Generic.IEnumerable&lt;Type&gt; remotingTypes, System.Fabric.ServiceContext serviceContext, object serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingMessageBodyFactory = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; remotingTypes, class System.Fabric.ServiceContext serviceContext, object serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory serviceRemotingMessageBodyFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.#ctor(System.Collections.Generic.IEnumerable{System.Type},System.Fabric.ServiceContext,System.Object,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher : seq&lt;Type&gt; * System.Fabric.ServiceContext * obj * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher (remotingTypes, serviceContext, serviceImplementation, serviceRemotingMessageBodyFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remotingTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="System.Object" />
        <Parameter Name="serviceRemotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
      </Parameters>
      <Docs>
        <param name="remotingTypes"><span data-ttu-id="130e1-106">ディスパッチできる型を要求するには</span><span class="sxs-lookup"><span data-stu-id="130e1-106">Types to which you can dispatch request to</span></span>  </param>
        <param name="serviceContext"><span data-ttu-id="130e1-107">サービス コンテキスト</span><span class="sxs-lookup"><span data-stu-id="130e1-107">Service context</span></span></param>
        <param name="serviceImplementation"><span data-ttu-id="130e1-108">指定されたリモート処理インターフェイスを実装するサービスの実装</span><span class="sxs-lookup"><span data-stu-id="130e1-108">Service implementation that implements specified remoting interfaces</span></span></param>
        <param name="serviceRemotingMessageBodyFactory"></param>
        <summary>
            <span data-ttu-id="130e1-109">特定のサービス コンテキストを使用し、指定されたサービスの実装にメッセージをディスパッチ ServiceRemotingDispatcher をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="130e1-109">Instantiates the ServiceRemotingDispatcher that uses the given service context and dispatches messages to the given service implementation.</span></span>
            <span data-ttu-id="130e1-110">このディスパッチャーは、リモート処理の指定した型への要求のディスパッチに使用できます。</span><span class="sxs-lookup"><span data-stu-id="130e1-110">This dispatcher can be used to dispatch request to the specified Remoting types.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="serviceRemotingMessageDispatcher.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="GetRemotingMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory GetRemotingMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.GetRemotingMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemotingMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory&#xA;override this.GetRemotingMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="serviceRemotingMessageDispatcher.GetRemotingMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.GetRemotingMessageBodyFactory</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="130e1-111">リモート処理の応答オブジェクトを作成するために使用 IServiceRemotingMessageBodyFactory を返します。</span><span class="sxs-lookup"><span data-stu-id="130e1-111">Returns a IServiceRemotingMessageBodyFactory used to create Remoting Response objects.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleOneWayMessage">
      <MemberSignature Language="C#" Value="public virtual void HandleOneWayMessage (Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void HandleOneWayMessage(class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.HandleOneWayMessage(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub HandleOneWayMessage (requestMessage As IServiceRemotingRequestMessage)" />
      <MemberSignature Language="F#" Value="abstract member HandleOneWayMessage : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; unit&#xA;override this.HandleOneWayMessage : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; unit" Usage="serviceRemotingMessageDispatcher.HandleOneWayMessage requestMessage" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.HandleOneWayMessage(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)</InterfaceMember>
      </Implements>
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
        <param name="requestMessage"><span data-ttu-id="130e1-112">要求メッセージ</span><span class="sxs-lookup"><span data-stu-id="130e1-112">Request message</span></span></param>
        <summary>
            <span data-ttu-id="130e1-113">クライアントから一方向のメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="130e1-113">Handles a one way message from the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleRequestResponseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt; HandleRequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.HandleRequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function HandleRequestResponseAsync (requestContext As IServiceRemotingRequestContext, requestMessage As IServiceRemotingRequestMessage) As Task(Of IServiceRemotingResponseMessage)" />
      <MemberSignature Language="F#" Value="abstract member HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;&#xA;override this.HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;" Usage="serviceRemotingMessageDispatcher.HandleRequestResponseAsync (requestContext, requestMessage)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler.HandleRequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher/&lt;HandleRequestResponseAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="requestMessage" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessage" />
      </Parameters>
      <Docs>
        <param name="requestContext"><span data-ttu-id="130e1-114">要求コンテキスト、要求に関する追加情報を含む</span><span class="sxs-lookup"><span data-stu-id="130e1-114">Request context - contains additional information about the request</span></span></param>
        <param name="requestMessage"><span data-ttu-id="130e1-115">要求メッセージ</span><span class="sxs-lookup"><span data-stu-id="130e1-115">Request message</span></span></param>
        <summary>
            <span data-ttu-id="130e1-116">サービスからの応答を必要とするクライアントからのメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="130e1-116">Handles a message from the client that requires a response from the service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleRequestResponseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; HandleRequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders requestMessageDispatchHeaders, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMessageBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; HandleRequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders requestMessageDispatchHeaders, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMessageBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.ServiceRemotingMessageDispatcher.HandleRequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;&#xA;override this.HandleRequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="serviceRemotingMessageDispatcher.HandleRequestResponseAsync (requestMessageDispatchHeaders, requestMessageBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestMessageDispatchHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V2.ServiceRemotingDispatchHeaders" />
        <Parameter Name="requestMessageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestMessageDispatchHeaders"><span data-ttu-id="130e1-117">要求メッセージ ヘッダー</span><span class="sxs-lookup"><span data-stu-id="130e1-117">Request message headers</span></span></param>
        <param name="requestMessageBody"><span data-ttu-id="130e1-118">要求メッセージの本文</span><span class="sxs-lookup"><span data-stu-id="130e1-118">Request message body</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="130e1-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="130e1-119">Cancellation token.</span></span> <span data-ttu-id="130e1-120">要求をキャンセルするために使用できます。</span><span class="sxs-lookup"><span data-stu-id="130e1-120">It can be used to cancel the request</span></span></param>
        <summary>
            <span data-ttu-id="130e1-121">サービスからの応答を必要とするクライアントからのメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="130e1-121">Handles a message from the client that requires a response from the service.</span></span> <span data-ttu-id="130e1-122">この Api は、クライアントがサービスと同じプロセスでは、ショート サーキットを使用できます。</span><span class="sxs-lookup"><span data-stu-id="130e1-122">This Api can be used for the short-circuiting where client is in same process as service.</span></span>
            <span data-ttu-id="130e1-123">直接、クライアントでは、ServiceProxy を使用する代わりにサービスへの要求をディスパッチできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="130e1-123">Client can now directly dispatch request to service instead of using ServiceProxy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>