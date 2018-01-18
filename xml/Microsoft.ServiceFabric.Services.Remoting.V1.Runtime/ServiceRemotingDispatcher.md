<Type Name="ServiceRemotingDispatcher" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher">
  <TypeSignature Language="C#" Value="public class ServiceRemotingDispatcher : IDisposable, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingDispatcher extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingDispatcher&#xA;Implements IDisposable, IServiceRemotingMessageHandler" />
  <TypeSignature Language="F#" Value="type ServiceRemotingDispatcher = class&#xA;    interface IServiceRemotingMessageHandler&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7e35b-101">実装を提供<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />サービスの実装にメッセージをディスパッチする<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="7e35b-101">Provides an implementation of <see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" /> that can dispatch messages to the service implementing <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingDispatcher (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher (serviceContext, service)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="service" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="7e35b-102">サービス コンテキスト</span><span class="sxs-lookup"><span data-stu-id="7e35b-102">Service context</span></span></param>
        <param name="service"><span data-ttu-id="7e35b-103">型のインターフェイスを実装するサービスの実装<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /></span><span class="sxs-lookup"><span data-stu-id="7e35b-103">Service implementation that implements interfaces of type <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /></span></span></param>
        <summary>
            <span data-ttu-id="7e35b-104">特定のサービス コンテキストを使用し、指定されたサービスの実装にメッセージをディスパッチ ServiceRemotingDispatcher をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="7e35b-104">Instantiates the ServiceRemotingDispatcher that uses the given service context and dispatches messages to the given service implementation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="serviceRemotingDispatcher.Dispose " />
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
        <summary>
            <span data-ttu-id="7e35b-105">アンマネージ リソースの解放またはリセットに関連付けられているアプリケーション定義のタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="7e35b-105">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <filterpriority><span data-ttu-id="7e35b-106">2</span><span class="sxs-lookup"><span data-stu-id="7e35b-106">2</span></span></filterpriority>
      </Docs>
    </Member>
    <Member MemberName="HandleOneWay">
      <MemberSignature Language="C#" Value="public virtual void HandleOneWay (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void HandleOneWay(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher.HandleOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub HandleOneWay (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member HandleOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit&#xA;override this.HandleOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="serviceRemotingDispatcher.HandleOneWay (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.HandleOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])</InterfaceMember>
      </Implements>
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
        <param name="requestContext"><span data-ttu-id="7e35b-107">要求コンテキスト、要求に関する追加情報を含む</span><span class="sxs-lookup"><span data-stu-id="7e35b-107">Request context - contains additional information about the request</span></span></param>
        <param name="messageHeaders"><span data-ttu-id="7e35b-108">要求メッセージ ヘッダー</span><span class="sxs-lookup"><span data-stu-id="7e35b-108">Request message headers</span></span></param>
        <param name="requestBody"><span data-ttu-id="7e35b-109">要求メッセージの本文</span><span class="sxs-lookup"><span data-stu-id="7e35b-109">Request message body</span></span></param>
        <summary>
            <span data-ttu-id="7e35b-110">クライアントから一方向のメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="7e35b-110">Handles a one way message from the client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RequestResponseAsync (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;&#xA;override this.RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="serviceRemotingDispatcher.RequestResponseAsync (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher/&lt;RequestResponseAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext"><span data-ttu-id="7e35b-111">要求コンテキスト、要求に関する追加情報を含む</span><span class="sxs-lookup"><span data-stu-id="7e35b-111">Request context - contains additional information about the request</span></span></param>
        <param name="messageHeaders"><span data-ttu-id="7e35b-112">要求メッセージ ヘッダー</span><span class="sxs-lookup"><span data-stu-id="7e35b-112">Request message headers</span></span></param>
        <param name="requestBody"><span data-ttu-id="7e35b-113">要求メッセージの本文</span><span class="sxs-lookup"><span data-stu-id="7e35b-113">Request message body</span></span></param>
        <summary>
            <span data-ttu-id="7e35b-114">サービスからの応答を必要とするクライアントからのメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="7e35b-114">Handles a message from the client that requires a response from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="7e35b-115">応答本文</span><span class="sxs-lookup"><span data-stu-id="7e35b-115">Response body</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>