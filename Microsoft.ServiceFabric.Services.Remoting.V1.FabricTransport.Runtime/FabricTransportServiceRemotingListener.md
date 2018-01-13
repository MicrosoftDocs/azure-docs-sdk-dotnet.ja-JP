<Type Name="FabricTransportServiceRemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener">
  <TypeSignature Language="C#" Value="public class FabricTransportServiceRemotingListener : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportServiceRemotingListener extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener, class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportServiceRemotingListener&#xA;Implements ICommunicationListener, IServiceRemotingListener" />
  <TypeSignature Language="F#" Value="type FabricTransportServiceRemotingListener = class&#xA;    interface IServiceRemotingListener&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
                <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレスおよびステートフルなサービスのインターフェイスのリモート処理を提供するファブリック TCP トランスポートを使用します。
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。 
            </param>
        <param name="serviceImplementation">
                サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。
                </param>
        <summary>
                既定値はファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="messageHandler">
                リモート処理のメッセージを処理するハンドラー。 メッセージは、受信したリスナーに送りますをこのハンドラーにします。
                </param>
        <summary>
                既定値はファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="serviceImplementation">
                サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。
                </param>
        <param name="listenerSettings">
                リスナーの設定。
            </param>
        <summary>
                指定されたファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.IService serviceImplementation, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.IService,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.IService * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, serviceImplementation, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="serviceImplementation" Type="Microsoft.ServiceFabric.Services.Remoting.IService" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="serviceImplementation">
                サービス実装オブジェクトを構築するために使用される<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />メッセージ処理のためです。
                </param>
        <param name="listenerSettingsConfigSectionName">
               構成パッケージの構成セクションの名前では、リスナーの設定を定義するサービス マニフェストで"Config"という名前です。 
               </param>
        <summary>
                ファブリック トランスポート ベース サービスのリモート処理のリスナーが構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />構成セクションから読み込まれます。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings listenerSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="messageHandler">
                リモート処理のメッセージを処理するハンドラー。 メッセージは、受信したリスナーに送りますをこのハンドラーにします。
                </param>
        <param name="listenerSettings">
                リスナーで使用する設定。
            </param>
        <summary>
                指定されたファブリック トランスポート ベース サービスのリモート処理リスナーの構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />です。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportServiceRemotingListener (System.Fabric.ServiceContext serviceContext, Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler messageHandler, string listenerSettingsConfigSectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.#ctor(System.Fabric.ServiceContext,Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener : System.Fabric.ServiceContext * Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener (serviceContext, messageHandler, listenerSettingsConfigSectionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="messageHandler" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
        <Parameter Name="listenerSettingsConfigSectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                リモート処理のリスナーが構築される、サービスのコンテキスト。
            </param>
        <param name="messageHandler">
                リモート処理のメッセージを処理するハンドラー。 メッセージは、受信したリスナーに送りますをこのハンドラーにします。
                </param>
        <param name="listenerSettingsConfigSectionName">
               構成パッケージの構成セクションの名前では、リスナーの設定を定義するサービス マニフェストで"Config"という名前です。 
               </param>
        <summary>
                ファブリック トランスポート ベース サービスのリモート処理のリスナーが構築<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />構成セクションから読み込まれます。
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
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
            このメソッドによって、通信リスナーを閉じます。 閉じる終了の状態は、このメソッドは、異常終了への移行。 このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.FabricTransport.Runtime.FabricTransportServiceRemotingListener.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
  </Members>
</Type>