<Type Name="WebHttpRelaySecurity" FullName="Microsoft.ServiceBus.WebHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class WebHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WebHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WebHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WebHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type WebHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>HTTP 要求を受信するために構成するサービス エンドポイントで使用できるセキュリティの種類を指定します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndWebHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndWebHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndWebHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> を伴う HTTP 要求を受信するために構成されるエンドポイントによって使用されるセキュリティのモードを、取得または設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" />エンドポイントによってトランスポート レベルのセキュリティ、資格情報専用、またはセキュリティが使用されるかどうかを示すです。 既定値は None です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値は、有効な EndToEndWebHttpSecurityMode ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービス クライアントによって使用されるリレー クライアント認証の種類を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。 既定値は、RelayClientAuthenticationType.RelayAccessToken です。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、バインディングのトランスポート レベルのセキュリティ設定を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" />バインディングを格納しています。 既定値の設定は、ClientCredentialType が [なし]、ProxyCredentialType が [なし]、およびレルム =""です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>