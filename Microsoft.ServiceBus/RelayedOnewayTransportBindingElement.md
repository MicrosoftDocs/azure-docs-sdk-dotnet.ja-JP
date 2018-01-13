<Type Name="RelayedOnewayTransportBindingElement" FullName="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class RelayedOnewayTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayedOnewayTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayedOnewayTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension" />
  <TypeSignature Language="F#" Value="type RelayedOnewayTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>一方向の通信に使用されるトランスポート バインド要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType">リレー クライアントの認証の種類。 これは、いずれかの<see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />または<see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />クラス、指定した認証の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (elementToClone As RelayedOnewayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement elementToClone" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToClone" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToClone">複製する要素。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />クラス、指定した要素を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType,Microsoft.ServiceBus.RelayedOnewayConnectionMode)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType * Microsoft.ServiceBus.RelayedOnewayConnectionMode -&gt; Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="new Microsoft.ServiceBus.RelayedOnewayTransportBindingElement (relayClientAuthenticationType, connectionMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="connectionMode" Type="Microsoft.ServiceBus.RelayedOnewayConnectionMode" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType">リレー クライアントの認証の種類。 これは、いずれかの<see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />または<see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />です。</param>
        <param name="connectionMode">接続モードです。 これは、いずれかの<see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Unicast" />または<see cref="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Multicast" />です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />クラス、指定された認証の種類と接続モードを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="relayedOnewayTransportBindingElement.BuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> バインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>指定したバインド コンテキストから初期化して、指定した型のチャネルを作成するには、チャネル ファクトリを作成します。</summary>
        <returns>列挙して、指定した型のチャネルを作成するためのチャネル ファクトリは、指定したバインド コンテキストから初期化されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="relayedOnewayTransportBindingElement.BuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> バインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>指定したバインド コンテキストから指定した種類のチャネルを受け入れるし、初期化するチャネル リスナーを作成します。</summary>
        <returns>指定した種類のチャネルを受け入れるし、指定したバインド コンテキストから初期化するチャネル リスナー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="relayedOnewayTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> このバインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>このバインド要素が、指定した型のチャネル ファクトリを作成できるかどうかを示す値を返します。</summary>
        <returns>true の場合、チャネル ファクトリを作成することができます。それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="relayedOnewayTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> このバインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>バインド要素が指定した種類のチャネルに対するチャネル リスナーを作成できるかどうかを示す値を返します。</summary>
        <returns>指定した型のチャネルのチャネル リスナーを作成できる場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはチャネルが切断されるまで初期化状態にすることができます、最大時間を設定します。</summary>
        <value>最大時間をチャネルが切断されるまで初期化状態にすることができます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="relayedOnewayTransportBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>このインスタンスのコピーを返します、<see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />バインド要素。</summary>
        <returns>このバインド要素のディープ クローンを格納するバインド要素。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントまたはサービスからネットワークでシリアル化されたメッセージの一部を転送するために使用されるバッファーのサイズを取得または設定します。</summary>
        <value>クライアントまたサービスからネットワークでシリアル化されたメッセージの一部を転送するために使用されるバッファーのサイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As RelayedOnewayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.RelayedOnewayConnectionMode with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインド要素で使用する接続モードを取得します。 接続モードには、いずれかを指定できます、<see cref="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" />列挙値。</summary>
        <value>このバインド要素で使用される接続モードです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPoolSettings As SocketConnectionPoolSettings" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.SocketConnectionPoolSettings" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketConnectionPoolSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>接続プールの現在のインスタンスの設定を取得します。</summary>
        <value>現在のインスタンスの接続プールの設定。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="relayedOnewayTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="context"> このバインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>存在する場合、バインド スタックの適切な層から要求された型のオブジェクトを返します。</summary>
        <returns>要求された型のオブジェクトの場合が見つかりました。それ以外の場合は null を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            URI が一致した場合にサービスに到達するためにホスト名を使用するかどうかを示す値を取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>保留可能なキュー内の接続要求の最大数を取得または設定します。</summary>
        <value>キュー内の接続の最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこのバインディングによって処理される着信メッセージを保持するバッファーのバイト単位の最大サイズを設定します。</summary>
        <value>このバインディングによって処理される着信メッセージを保持するバッファーのバイトの最大サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージまたはメッセージの一部を保持できるメモリにバッファー送信する前に最長期間を設定します。</summary>
        <value>最大間隔になる前にメモリにバッファーされるメッセージまたはメッセージの一部を保持できる時間の送信。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービスでの着信接続処理に使用できる、保留中の非同期受け入れスレッドの最大数を取得または設定します。</summary>
        <value>サービスでの着信接続処理に使用できる保留中の非同期受け入れスレッドの最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>保留する最大接続数を取得または設定します。</summary>
        <value>保留状態の接続の最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、このバインド要素によって使用される Azure アクセス制御の認証の種類を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />をこのバインド要素によって使用される認証の種類を表すです。既定値は<see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインド要素によって使用される URI スキームを取得します。</summary>
        <value>このバインド要素によって使用される URI スキーム。 返される値は、"sb"です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportPolicy (exporter As MetadataExporter, context As PolicyConversionContext) Implements IPolicyExportExtension.ExportPolicy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.MetadataExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.PolicyConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">エクスポート プロセスを変更に使用できる MetadataExporter です。</param>
        <param name="context">カスタム ポリシー アサーションの挿入に使用できる PolicyConversionContext です。</param>
        <summary>
            このバインドに関するカスタム ポリシー アサーションをエクスポートします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>