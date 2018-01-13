<Type Name="WSHttpRelaySecurity" FullName="Microsoft.ServiceBus.WSHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class WSHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WSHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WSHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type WSHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> のセキュリティ設定を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As NonDualMessageSecurityOverRelayHttp" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この Azure Service Bus バインドのメッセージ レベルのセキュリティ設定を取得します。</summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.NonDualMessageSecurityOverRelayHttp" />です。セキュリティ設定が含まれています。 既定値が含まれています: true に設定された既定 EstablishSecurityContext、ClientCredentialType は Windows AlgorithmSuite Basic256、かつが NegotiateServiceCredential は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この Azure Service Bus バインドのメッセージ セキュリティ モードを指定します。 </summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />です。この Azure Service Bus バインドのセキュリティ モードが含まれています。 既定値は、トランスポートです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービス アプリケーションまたはクライアント アプリケーションを Azure Service Bus に提供するために必要な認証の種類を設定します。</summary>
        <value>サービス アプリケーションまたはクライアント アプリケーションを Azure Service Bus に提供するために必要な認証の種類。 既定では、 <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.WSHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この Azure Service Bus バインドのトランスポート レベルのセキュリティ設定を格納しているオブジェクトを取得します。 </summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" />です。この項目のトランスポート セキュリティが含まれています。 既定値には、ClientCredentialType が [なし] と、ProxyCredentialType が [なし] が含まれています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>