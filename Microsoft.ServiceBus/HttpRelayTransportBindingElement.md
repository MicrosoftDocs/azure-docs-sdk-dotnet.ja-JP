<Type Name="HttpRelayTransportBindingElement" FullName="Microsoft.ServiceBus.HttpRelayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class HttpRelayTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Channels.ITransportTokenAssertionProvider, System.ServiceModel.Description.IPolicyExportExtension, System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpRelayTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Channels.ITransportTokenAssertionProvider, class System.ServiceModel.Description.IPolicyExportExtension, class System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpRelayTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension, ITransportTokenAssertionProvider, IWsdlExportExtension" />
  <TypeSignature Language="F#" Value="type HttpRelayTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension&#xA;    interface IWsdlExportExtension&#xA;    interface ITransportTokenAssertionProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.ITransportTokenAssertionProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>Azure Service Bus にメッセージを送信するための HTTP トランスポートを指定するために使用するバインド要素を表します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HttpRelayTransportBindingElement (Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.HttpRelayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (elementToBeCloned As HttpRelayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpRelayTransportBindingElement : Microsoft.ServiceBus.HttpRelayTransportBindingElement -&gt; Microsoft.ServiceBus.HttpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToBeCloned" Type="Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToBeCloned">複製対象となる要素。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />クラス、クローンを作成する、指定した要素を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpRelayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.HttpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpRelayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType">クライアント認証の種類。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />クラス、指定したクライアント認証の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントがクッキーを受け入れて、それらを今後の要求に反映させるかどうかを示す値を取得または設定します。</summary>
        <value>cookie を許可する場合は true。それ以外の場合は false です。 既定値は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="httpRelayTransportBindingElement.BuildChannelFactory context" />
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
        <param name="context"> チャネルのバインド コンテキスト。</param>
        <summary>チャネルを作成するために使用できるチャネル ファクトリを作成します。</summary>
        <returns>指定した型のチャネル ファクトリ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="httpRelayTransportBindingElement.BuildChannelListener context" />
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
        <param name="context"> バインド コンテキスト。</param>
        <summary>指定されたジェネリック型のチャネルに対するチャネル リスナーを作成します。</summary>
        <returns>チャネル リスナー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="httpRelayTransportBindingElement.CanBuildChannelFactory context" />
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
        <param name="context"> チャネルのバインド コンテキスト。</param>
        <summary>指定した種類のチャネル ファクトリを作成できるかどうかを判断します。</summary>
        <returns>true の場合、チャネル ファクトリを作成することができます。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="httpRelayTransportBindingElement.CanBuildChannelListener context" />
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
        <param name="context"> バインド要素のコンテキストを提供するバインディング コンテキスト。</param>
        <summary>指定した種類のチャネルに対するリスナーをバインド要素が作成できるかどうかを示す値を返します。</summary>
        <returns>true の場合、IChannelListener&lt;TChannel&gt;の型 IChannel できるは、それ以外のバインド要素によって作成 false。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> コンテキストが null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="httpRelayTransportBindingElement.Clone " />
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
        <summary>バインド要素オブジェクトのコピーを返します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.BindingElement" />オリジナルのディープ クローンを格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected virtual System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CreateInnerChannelBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateInnerChannelBindingElement () As HttpTransportBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateInnerChannelBindingElement : unit -&gt; System.ServiceModel.Channels.HttpTransportBindingElement&#xA;override this.CreateInnerChannelBindingElement : unit -&gt; System.ServiceModel.Channels.HttpTransportBindingElement" Usage="httpRelayTransportBindingElement.CreateInnerChannelBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.HttpTransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>作成、<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルにします。</summary>
        <returns>A<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルにします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="httpRelayTransportBindingElement.GetProperty context" />
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
        <param name="context"> バインド コンテキスト。</param>
        <summary>指定したバインド コンテキストから指定したプロパティを取得します。</summary>
        <returns>指定したバインド コンテキストからプロパティです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransportTokenAssertion">
      <MemberSignature Language="C#" Value="public System.Xml.XmlElement GetTransportTokenAssertion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.XmlElement GetTransportTokenAssertion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.GetTransportTokenAssertion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTransportTokenAssertion () As XmlElement" />
      <MemberSignature Language="F#" Value="abstract member GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement&#xA;override this.GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement" Usage="httpRelayTransportBindingElement.GetTransportTokenAssertion " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.ITransportTokenAssertionProvider.GetTransportTokenAssertion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>セキュリティ バインドで使用されるトランスポート トークンを表す XML 要素を取得します。</summary>
        <returns>セキュリティ バインドで使用されるトランスポート トークンです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはホスト名比較モードを使用するを設定します。</summary>
        <value>ホスト名に、比較モードを使用します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected virtual void InitializeInnerChannelBindingElement (System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void InitializeInnerChannelBindingElement(class System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.InitializeInnerChannelBindingElement(System.ServiceModel.Channels.HttpTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub InitializeInnerChannelBindingElement (httpTransportElement As HttpTransportBindingElement)" />
      <MemberSignature Language="F#" Value="abstract member InitializeInnerChannelBindingElement : System.ServiceModel.Channels.HttpTransportBindingElement -&gt; unit&#xA;override this.InitializeInnerChannelBindingElement : System.ServiceModel.Channels.HttpTransportBindingElement -&gt; unit" Usage="httpRelayTransportBindingElement.InitializeInnerChannelBindingElement httpTransportElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpTransportElement" Type="System.ServiceModel.Channels.HttpTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="httpTransportElement"> 初期化するためにバインド要素。</param>
        <summary>現在のインスタンスの設定で指定されたバインド要素の初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />バインド要素。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはバインド要素が動的かどうかを設定します。</summary>
        <value>バインド要素が動的; 場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveEnabled">
      <MemberSignature Language="C#" Value="public bool KeepAliveEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool KeepAliveEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.KeepAliveEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.KeepAliveEnabled : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.KeepAliveEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービス エンドポイントへの永続的な接続を行うかどうかを示す値を取得または設定します。 </summary>
        <value>true の場合は、サービス エンドポイントに要求がキープ アライブ; の値を持つ接続 HTTP ヘッダーを含める必要があります。それ以外の場合は false です。 既定値は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>使用するバッファーの最大サイズを取得または設定します。</summary>
        <value>バッファーのバイト単位の最大サイズを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>HTTP 要求に使用するプロキシのアドレスを格納する URI を取得または設定します。</summary>
        <value>返します、<see cref="T:System.Uri" />プロキシのアドレスを格納します。 既定値は NULL です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAuthenticationScheme">
      <MemberSignature Language="C#" Value="public System.Net.AuthenticationSchemes ProxyAuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.AuthenticationSchemes ProxyAuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAuthenticationScheme As AuthenticationSchemes" />
      <MemberSignature Language="F#" Value="member this.ProxyAuthenticationScheme : System.Net.AuthenticationSchemes with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.AuthenticationSchemes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>HTTP プロキシにより処理されるクライアント要求の認証に使用する認証方式を取得または設定します。</summary>
        <value>値のいずれか、<see cref="T:System.Net.AuthenticationSchemes" />プロキシでのクライアント認証を使用するプロトコルを指定する列挙体です。 既定は Anonymous です。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレー クライアントの認証の種類を設定します。 </summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />です。認証の種類が含まれています。 既定値は RelayClientAuthenticationType.RelayAccessToken</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トランスポートの URI スキームを取得します。</summary>
        <value>URI スキームを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
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
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportContract">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportContract (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportContract(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportContract (exporter As WsdlExporter, context As WsdlContractConversionContext) Implements IWsdlExportExtension.ExportContract" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlContractConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">この WsdlExporter は、コントラクト情報をエクスポートします。</param>
        <param name="context">エクスポートされた WSDL 要素からコントラクトの説明へのマッピングを提供します。</param>
        <summary>
            コントラクトに対して生成される Web サービス記述言語 (WSDL) に、カスタム WSDL 要素を書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportEndpoint (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlEndpointConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlEndpointConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportEndpoint (exporter As WsdlExporter, context As WsdlEndpointConversionContext) Implements IWsdlExportExtension.ExportEndpoint" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlEndpointConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">この WsdlExporter は、コントラクト情報をエクスポートします。</param>
        <param name="context">エクスポートされた WSDL 要素からコントラクトの説明へのマッピングを提供します。</param>
        <summary>
            エンドポイントに対して生成される Web サービス記述言語 (WSDL) に、カスタム WSDL 要素を書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>転送モードを取得または設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />転送モードを格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ユーザー固有の設定ではなく、コンピューター全体のプロキシ設定を使用するかどうかを示す値を取得または設定します。</summary>
        <value>true の場合は、コンピューター全体のプロキシ設定が使用されます。それ以外の場合は false です。 既定値は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>