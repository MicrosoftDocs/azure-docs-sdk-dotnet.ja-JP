<Type Name="BasicHttpRelaySecurity" FullName="Microsoft.ServiceBus.BasicHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type BasicHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>セキュリティ設定を構成するためのプロパティを提供する<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />バインドします。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.BasicHttpRelayMessageSecurity Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.BasicHttpRelayMessageSecurity Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BasicHttpRelayMessageSecurity" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.BasicHttpRelayMessageSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> バインディングのメッセージ レベルのセキュリティ設定を取得します。</summary>
        <value>返します、 <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />、このバインディングのメッセージ レベルのセキュリティ設定を表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndBasicHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> バインディングのセキュリティ モードを取得または設定します。</summary>
        <value>値のいずれかの<see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />列挙します。 既定値は None です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が、<see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" /> にとって有効な値ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Azure Service Bus サービスで使用される認証の種類を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />サービスで使用される認証の種類を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.BasicHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> バインディングのトランスポート レベルのセキュリティ設定を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" />セキュリティ設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>