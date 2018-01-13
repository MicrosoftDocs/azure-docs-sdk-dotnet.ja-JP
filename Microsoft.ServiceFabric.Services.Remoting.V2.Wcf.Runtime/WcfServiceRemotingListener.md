<Type Name="WcfServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class WcfServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type WcfServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレスおよびステートフルなサービスのインターフェイスのリモート処理を提供する Windows Communication Foundation を使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, System.ServiceModel.Channels.Binding listenerBinding = null, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class System.ServiceModel.Channels.Binding listenerBinding, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.ServiceModel.Channels.Binding,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * System.ServiceModel.Channels.Binding * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, serviceImplementation, listenerBinding, serializationProvider, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="serviceImplementation">サービス実装オブジェクト。</param>
        <param name="listenerBinding">リスナーに対して使用する WCF バインドします。 場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
            </param>
        <param name="serializationProvider"></param>
        <param name="endpointResourceName">アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。 EndpointResourceName が指定されているか null でない場合は、既定値"ServiceEndpointV2"が使用されます。
            </param>
        <summary>
            サービスのリモート処理のリスナーを WCF 構成要素に基づいています。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="messageHandler">リモート処理のメッセージの受信と処理ハンドラー。 メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding">リスナーに対して使用する WCF バインドします。 場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。
            </param>
        <param name="address">WCF のリスナーを使用するエンドポイント アドレス。 指定しない場合、"ServiceEndpointV2"サービス マニフェストで定義されているをという名前の既定のエンドポイント リソースを使用して、エンドポイント アドレスが作成された指定されているか null です。 
            </param>
        <summary>
            サービスのリモート処理のリスナーを WCF 構成要素に基づいています。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider = null, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = &quot;ServiceEndpointV2&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider serializationProvider, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener (serviceContext, messageHandler, serializationProvider, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="serializationProvider" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">リモート処理のリスナーが構築される、サービスのコンテキスト。</param>
        <param name="messageHandler">リモート処理のメッセージの受信と処理ハンドラー。 メッセージが受信されると、リスナーはハンドラーに、メッセージを配信します。
            </param>
        <param name="serializationProvider"></param>
        <param name="listenerBinding">リスナーに対して使用する WCF バインドします。 場合は、リスナーのバインドが指定されていないか、null、既定のリスナーをバインディングを使用して作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />を作成する方法、<see cref="T:System.ServiceModel.NetTcpBinding" />セキュリティなし。
            </param>
        <param name="endpointResourceName">アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。 EndpointResourceName が指定されていないか、null、既定値"ServiceEndpointV2"が使用されます。
            </param>
        <summary>
            サービスのリモート処理のリスナーを WCF 構成要素に基づいています。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このメソッドによって、通信リスナーを閉じます。 閉じる終了の状態は、このメソッドは、異常終了への移行。 このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            このメソッドによって、通信リスナーを閉じます。 終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            このメソッドによって、通信リスナーを開くことができません。 Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、エンドポイントの文字列です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.Runtime.WcfServiceRemotingListener.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                取得、<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。
                </summary>
        <value>
                A<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。
                </value>
        <remarks>
                サービス ホストは、そのコンス トラクターでリスナーを作成します。 使用して、ランタイムによってこのような通信する前にリスナーが開かれました<see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />メソッドでは、このプロパティを介してアクセスすると、サービス ホストをカスタマイズできます。
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>