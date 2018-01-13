<Type Name="NetOnewayRelaySecurity" FullName="Microsoft.ServiceBus.NetOnewayRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class NetOnewayRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetOnewayRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetOnewayRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetOnewayRelaySecurity" />
  <TypeSignature Language="F#" Value="type NetOnewayRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>セキュリティ設定のコレクション、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />バインドします。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.MessageSecurityOverRelayOneway Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.MessageSecurityOverRelayOneway Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayOneway" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.MessageSecurityOverRelayOneway" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.MessageSecurityOverRelayOneway</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> を使用して構成されたサービスの、メッセージ レベルのセキュリティ要件の種類を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayOneway" />エンドポイントのメッセージ レベルのセキュリティ要件の種類を示すです。 AlgorithmSuite 既定値は Basic256 で、既定値 ClientCredentialType は Windows です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> を使用して構成されたエンドポイントで使用されるセキュリティ レベル (メッセージ レベルまたはトランスポート レベル) を取得するかどうかを設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />エンドポイントによるメッセージ レベルまたはトランスポート レベルのセキュリティが使用されるかどうかを示すです。 既定値は、Transport です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">セキュリティ モードの値が正しくありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレー クライアントの認証の種類を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />認証の種類を格納しています。 既定値は <see cref="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" /> です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が有効な<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />フィールドです。</exception>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayedOnewayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.RelayedOnewayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As RelayedOnewayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.RelayedOnewayTransportSecurity" Usage="Microsoft.ServiceBus.NetOnewayRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>構成されているエンドポイントのトランスポート レベルのセキュリティ要件の種類を取得、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />です。 既定値は EncryptAndSign です。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportSecurity" />エンドポイントのトランスポート レベルのセキュリティ要件の種類を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>