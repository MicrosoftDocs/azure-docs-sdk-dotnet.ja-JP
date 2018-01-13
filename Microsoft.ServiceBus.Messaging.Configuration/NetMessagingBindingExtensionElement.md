<Type Name="NetMessagingBindingExtensionElement" FullName="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingBindingExtensionElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingBindingExtensionElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingBindingExtensionElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetMessagingBindingExtensionElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>構成を指定する XML 要素を表します<see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />です。</summary>
    <remarks>
            NetMessagingTransportBindingElement、NetMessagingBinding は、簡単に ServiceBus のメッセージング エンティティ (キュー、トピック、およびサブスクリプション) へのメッセージを送受信する WCF クライアントを許可します。  
             これらのメッセージ交換では、標準の WCF プログラミング IOutputChannel、IInputChannel、IInputSessionChannel、ReceiveContext などのモデルを使用します。  
            NetMessagingTransportBindingElement は、作成元の IOutputChannel、IInputChannel、IInputChannel + ReceiveContext、IInputSessionChannel、および IInputSessionChannel + ReceiveContext をサポートします。  セッションフル チャネル (IInputSessionChannel、IInputSessionChannel + ReceiveContext) はセッションまたはメッセージ交換をサポートします。
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBindingExtensionElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBindingExtensionElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement : string -&gt; Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" Usage="new Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">名前。</param>
        <summary>指定された名前を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用されているバインド要素の型を取得します。
            </summary>
        <value> 使用されているバインド要素の型。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netMessagingBindingExtensionElement.InitializeFrom binding" />
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
        <param name="binding"> バインディング。 </param>
        <summary> このバインド構成要素を、指定されたバインディングの内容で初期化します。 </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="binding" /> が null です。
            </exception>
        <exception cref="T:System.ArgumentException">
            このバインディング要素の種類が、<paramref name="binding" /> で指定された種類と異なります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netMessagingBindingExtensionElement.OnApplyConfiguration binding" />
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
        <param name="binding"> バインディング。 </param>
        <summary> 指定されたバインド要素の内容をこのバインド構成要素に適用するときに呼び出されます。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("prefetchCount", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはプリフェッチ数を設定します。</summary>
        <value>プリフェッチ数。</value>
        <remarks> サーバーに次の受信呼び出しで有効になります </remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> オブジェクトのコレクションが格納されている <see cref="T:System.Configuration.ConfigurationProperty" /> インスタンスを取得します。オブジェクトは、この構成要素の属性または <see cref="T:System.Configuration.ConfigurationElement" /> オブジェクトです。 </summary>
        <value> <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> オブジェクトのコレクションが格納されている <see cref="T:System.Configuration.ConfigurationProperty" /> インスタンス。このオブジェクトは、この構成要素の属性または <see cref="T:System.Configuration.ConfigurationElement" /> オブジェクトです。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sessionIdleTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.PositiveTimeSpanValidator</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、SessionIdleTimeout を設定します。</summary>
        <value>IInputSessionChannel.TryReceive 操作は、この期間内のメッセージを受信しない場合、チャネルの間でのセッションの終了が示されます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransportSettings As NetMessagingTransportSettingsElement" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingBindingExtensionElement.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transportSettings", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または net メッセージングのトランスポート設定要素を設定します。</summary>
        <value>Net メッセージング トランスポート設定要素。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>