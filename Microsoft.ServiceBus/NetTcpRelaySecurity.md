<Type Name="NetTcpRelaySecurity" FullName="Microsoft.ServiceBus.NetTcpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class NetTcpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetTcpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetTcpRelaySecurity" />
  <TypeSignature Language="F#" Value="type NetTcpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントで使用される、トランスポート レベルとメッセージ レベルのセキュリティの種類を指定します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayConnection" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.MessageSecurityOverRelayConnection" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.MessageSecurityOverRelayConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたサービスの、メッセージ レベルのセキュリティ要件の種類を取得します。 </summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" />エンドポイントのメッセージ レベルのセキュリティ要件の種類を示すです。 既定のセキュリティ設定は、:、; ユーザー名の ClientCredentialTypeAlgorithmSuite Basic256 のです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントで使用されるセキュリティ レベル (メッセージ レベルまたはトランスポート レベル) を取得するかどうかを設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />エンドポイントによるメッセージ レベルまたはトランスポート レベルのセキュリティが使用されるかどうかを示すです。 既定値は、Transport です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が有効な<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />フィールドです。</exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
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
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が有効な<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />フィールドです。</exception>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TcpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As TcpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.TcpRelayTransportSecurity" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントの、メッセージ レベルのセキュリティ要件の種類を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" />エンドポイントのトランスポート レベルのセキュリティ要件の種類を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>