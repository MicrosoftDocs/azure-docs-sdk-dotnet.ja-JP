<Type Name="WS2007HttpRelayBinding" FullName="Microsoft.ServiceBus.WS2007HttpRelayBinding">
  <TypeSignature Language="C#" Value="public class WS2007HttpRelayBinding : Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WS2007HttpRelayBinding extends Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class WS2007HttpRelayBinding&#xA;Inherits WSHttpRelayBinding" />
  <TypeSignature Language="F#" Value="type WS2007HttpRelayBinding = class&#xA;    inherit WSHttpRelayBinding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.WSHttpRelayBinding</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>派生した相互運用可能なバインドを表す<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />セキュリティ、ReliableSession、および transactionflow の各バインド要素の更新バージョンをサポートしています。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>バインドで使用されるセキュリティの種類を指定して、<see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> クラスの新しいインスタンスを初期化します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (string configName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : string -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding configName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configName">バインド構成の名前、<see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /></param>
        <summary>構成名で指定されたバインディングを使用して、<see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode">SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類を指定するセキュリティ モード。</param>
        <param name="relayClientAuthenticationType">クライアントで使用される認証の種類。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />クラス バインドで使用されるセキュリティとリレーのクライアント認証の種類を指定しています。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WS2007HttpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType * bool -&gt; Microsoft.ServiceBus.WS2007HttpRelayBinding" Usage="new Microsoft.ServiceBus.WS2007HttpRelayBinding (securityMode, relayClientAuthenticationType, reliableSessionEnabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="securityMode">SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類を指定します。</param>
        <param name="relayClientAuthenticationType">クライアントで使用される認証の種類。</param>
        <param name="reliableSessionEnabled">信頼できるセッションが有効である場合は true。それ以外の場合は false です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.WS2007HttpRelayBinding" />クラス バインド、クライアントのリレーと信頼できるセッションが有効になっているかどうかを示す値に指定された認証で使用されるセキュリティの種類を指定しています。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WS2007HttpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wS2007HttpRelayBinding.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のバインドからセキュリティ バインド要素を取得します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />現在のセキュリティ バインド要素を格納しています。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>