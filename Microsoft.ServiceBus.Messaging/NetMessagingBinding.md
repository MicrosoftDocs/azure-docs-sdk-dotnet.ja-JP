<Type Name="NetMessagingBinding" FullName="Microsoft.ServiceBus.Messaging.NetMessagingBinding">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingBinding : System.ServiceModel.Channels.Binding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingBinding extends System.ServiceModel.Channels.Binding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingBinding&#xA;Inherits Binding" />
  <TypeSignature Language="F#" Value="type NetMessagingBinding = class&#xA;    inherit Binding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Net メッセージングに使用されるバインディングを表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.NetMessagingBinding : string -&gt; Microsoft.ServiceBus.Messaging.NetMessagingBinding" Usage="new Microsoft.ServiceBus.Messaging.NetMessagingBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">初期化に使用する構成。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netMessagingBinding.CreateBindingElements " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElementCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを返します。</summary>
        <returns><see cref="T:System.ServiceModel.Channels.BindingElementCollection" />オブジェクトによって記述されたバインド要素の順序付けられたスタックを含む、<see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingBinding" />です。 ボトムアップからバインド要素の順序は、トランスポート、エンコーディング、およびセキュリティです。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(524288)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バインドによって処理される TCP メッセージを保存するバッファー プールの最大サイズを取得または設定します。</summary>
        <value>バインドによって処理される TCP メッセージを保存するバッファー プールの最大サイズ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(-1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの受信者を事前にフェッチするメッセージの数を設定します。</summary>
        <value>メッセージの受信者を事前にフェッチするメッセージの数。</value>
        <remarks> サーバーに次の受信呼び出しで有効になります。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングで構成されたチャネルとリスナーのための URI トランスポート スキームを取得します。</summary>
        <value>チャネルとリスナーがこのバインディングで構成されているの URI トランスポート スキーム。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(typeof(System.TimeSpan), "00:01:00")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッションがタイムアウトするまでに待機する非アクティブな期間を指定する timespan 値を設定します。</summary>
        <value>セッションがタイムアウトするまでに待機する非アクティブな期間を指定する timespan 値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingBinding.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingBinding.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または net メッセージング用のトランスポート設定を設定します。</summary>
        <value>Net メッセージングのトランスポート設定。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>