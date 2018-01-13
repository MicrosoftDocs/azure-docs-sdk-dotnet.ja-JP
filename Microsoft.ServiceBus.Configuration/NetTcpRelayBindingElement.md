<Type Name="NetTcpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Azure Service Bus リレーを介してコンピューター間通信に適した、セキュリティで保護された信頼できるバインディングを説明する構成要素。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">バインド構成の名前。</param>
        <summary>構成名を指定して、<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この構成要素の型を取得します。 (StandardBindingElement.BindingElementType をオーバーライドします)。</summary>
        <value>返します、<see cref="T:System.Type" />構成要素の型を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、この構成用の App.config ファイルに格納されている接続モードを設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />既定値が転送される接続モードを格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> 初期化するためにバインドします。</param>
        <summary>指定したバインディングのプロパティ値からこのバインド構成要素の内容を初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレー バインドが動的かどうかを設定します。</summary>
        <value>リレー バインドは、動的; 場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリスナーで受け入れられるを待機できるチャネルの最大数を指定する App.config ファイルで値を設定します。</summary>
        <value>保留可能なキュー内の接続要求の最大数を返します。 既定値は 10 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、バインディングによって処理される TCP メッセージを格納するバッファー プールの最大サイズを含む App.config ファイルから値を設定します。</summary>
        <value>バインディングによって処理されるメッセージを格納するバッファー プールに入力できる最大サイズを返します。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージをメモリに格納するために使用するバッファーのバイト単位で最大のサイズを指定する App.config ファイルから値を設定します。</summary>
        <value>メモリ内でメッセージの保存に使用されるバッファーの最大サイズ (バイト単位)。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービスを作成および受け入れる発信/着信接続の最大数を指定する App.config ファイルから値を設定します。</summary>
        <value>クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、このバインディングで構成されるチャネルで受信可能なメッセージの最大サイズを含む App.config ファイルから値を設定します。</summary>
        <value>(バイト単位) は、バインディングによって処理されるメッセージの最大サイズを返します。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> 設定を更新するバインディング。</param>
        <summary>指定されたバインド要素をこの構成要素の設定を適用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納する ConfigurationPropertyCollection インスタンスを取得します。 (StandardBindingElement.Properties をオーバーライドします)。</summary>
        <value>属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を課すを App.config ファイルから値を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" />交換される SOAP メッセージに対する複雑さの制約を指定します。 これらの制約の既定値については、後の「解説」で説明します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("reliableSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>チャネルのエンドポイント間に信頼できるセッションを確立するかどうかを指定する構成要素を取得します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" />チャネルのエンドポイント間に WS-RM 信頼できるセッションが確立するかどうかを示すです。 既定値は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングで使用されるセキュリティの種類を決定する App.config ファイルから値を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />関連付けられているバインディングのセキュリティ設定を格納しています。 既定値は none です。<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />関連付けられているから取得する、NetTcpRelayBinding でバインドが直接作成されます。 そのため、バインドを作成すると後も、新しいバインディングを作成しない限り、新しいオブジェクトにこのオブジェクトを置き換えることはできません。 ただし、WebHttpRelaySecurity の多くのメンバーは、セキュリティのプロパティを設定できます。 バインディングのセキュリティの詳細については、セキュリティと保護のセクションを参照してください。 と共に、トランスポートとエンコードの種類は、セキュリティ設定は、このバインディングを定義する 3 つの主要なプロパティのいずれかを表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージをバッファリングまたはストリームするかどうか、または要求を指定する App.config ファイルから値を設定または応答します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />を格納しているサービスをストリームまたはバッファー内のバインドを使用して (または両方) が構成されているかどうかを示すメッセージ転送のモード。 使用可能な値は次のとおり: BufferedStreamedStreamedRequestStreamedResponseThe 既定値は Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> Streamed に StreamedRequest と StreamedResponse の両方を意味します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>