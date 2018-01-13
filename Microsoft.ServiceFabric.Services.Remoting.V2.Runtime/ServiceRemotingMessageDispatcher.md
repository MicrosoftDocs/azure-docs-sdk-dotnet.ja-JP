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
            実装を提供<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V2.Runtime.IServiceRemotingMessageHandler" />サービスの実装にメッセージをディスパッチする<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。
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
        <param name="serviceContext">サービス コンテキスト</param>
        <param name="serviceImplementation">型のインターフェイスを実装するサービスの実装<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /></param>
        <param name="serviceRemotingMessageBodyFactory">これは、リモート処理の応答オブジェクトを作成するディスパッチャーによって使用されるファクトリ</param>
        <summary>
            特定のサービス コンテキストを使用し、指定されたサービスの実装にメッセージをディスパッチ ServiceRemotingDispatcher をインスタンス化します。
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
        <param name="remotingTypes">ディスパッチできる型を要求するには  </param>
        <param name="serviceContext">サービス コンテキスト</param>
        <param name="serviceImplementation">指定されたリモート処理インターフェイスを実装するサービスの実装</param>
        <param name="serviceRemotingMessageBodyFactory"></param>
        <summary>
            特定のサービス コンテキストを使用し、指定されたサービスの実装にメッセージをディスパッチ ServiceRemotingDispatcher をインスタンス化します。
            このディスパッチャーは、リモート処理の指定した型への要求のディスパッチに使用できます。
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
            リモート処理の応答オブジェクトを作成するために使用 IServiceRemotingMessageBodyFactory を返します。
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
        <param name="requestMessage">要求メッセージ</param>
        <summary>
            クライアントから一方向のメッセージを処理します。
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
        <param name="requestContext">要求コンテキスト、要求に関する追加情報を含む</param>
        <param name="requestMessage">要求メッセージ</param>
        <summary>
            サービスからの応答を必要とするクライアントからのメッセージを処理します。
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
        <param name="requestMessageDispatchHeaders">要求メッセージ ヘッダー</param>
        <param name="requestMessageBody">要求メッセージの本文</param>
        <param name="cancellationToken">キャンセル トークン。 要求をキャンセルするために使用できます。</param>
        <summary>
            サービスからの応答を必要とするクライアントからのメッセージを処理します。 この Api は、クライアントがサービスと同じプロセスでは、ショート サーキットを使用できます。
            直接、クライアントでは、ServiceProxy を使用する代わりにサービスへの要求をディスパッチできるようになりました。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>