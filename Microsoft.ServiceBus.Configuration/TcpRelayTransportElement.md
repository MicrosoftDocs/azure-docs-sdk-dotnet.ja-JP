<Type Name="TcpRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement">
  <TypeSignature Language="C#" Value="public sealed class TcpRelayTransportElement : Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TcpRelayTransportElement extends Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TcpRelayTransportElement&#xA;Inherits ConnectionOrientedTransportElement" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportElement = class&#xA;    inherit ConnectionOrientedTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>チャネルがカスタム バインドに含まれているときに TCP トランスポートでメッセージを転送する構成要素を指定します。 このクラスは継承できません。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"> 設定を更新するバインド要素。</param>
        <summary>指定されたバインド要素をこの構成要素の設定を適用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインド要素の型を取得します。</summary>
        <value>返します、<see cref="T:System.Type" />バインディング要素の型を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
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
        <value>返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />接続モードを格納しています。 既定の設定を転送します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionPoolSettings As SocketConnectionPoolSettingsElement" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionPoolSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または現在のインスタンスの接続プール設定を記述する XML 値を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" />に現在のインスタンスを適用するバインド要素によって使用される接続プールの設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="tcpRelayTransportElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> コピーする構成要素。</param>
        <summary>指定された構成要素の内容をこの構成要素にコピーします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="tcpRelayTransportElement.CreateDefaultBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>この構成要素の設定からバインド要素を作成します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />既定のバインド要素を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.InitializeFrom bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement">初期化するためにバインド要素。</param>
        <summary>このバインド構成要素を、指定されたバインド要素の内容で初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
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
        <summary>取得または保留可能なキューに置かれた接続要求の最大数を表す XML 値を設定します。</summary>
        <value>保留可能なキュー内の接続要求の最大数を返します。 既定値は 10 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティのコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレー クライアントの認証の種類を表す XML 値を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。 既定値は、RelayClientAuthenticationType.RelayAccessToken です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>