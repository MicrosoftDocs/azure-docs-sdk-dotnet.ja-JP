<Type Name="HttpsRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement">
  <TypeSignature Language="C#" Value="public class HttpsRelayTransportElement : Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpsRelayTransportElement extends Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpsRelayTransportElement&#xA;Inherits HttpRelayTransportElement" />
  <TypeSignature Language="F#" Value="type HttpsRelayTransportElement = class&#xA;    inherit HttpRelayTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.HttpRelayTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Azure サービス バス経由で SOAP メッセージを送信するための HTTPS トランスポートを指定する構成要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpsRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バインド要素の型を取得します。</summary>
        <value>バインド要素の型。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="httpsRelayTransportElement.CreateDefaultBindingElement " />
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
        <returns>返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />プロパティを持つは、この構成要素の設定からコピーされます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>