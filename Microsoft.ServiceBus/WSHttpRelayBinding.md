<Type Name="WSHttpRelayBinding" FullName="Microsoft.ServiceBus.WSHttpRelayBinding">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBinding : Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBinding extends Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBinding&#xA;Inherits WSHttpRelayBindingBase" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBinding = class&#xA;    inherit WSHttpRelayBindingBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.WSHttpRelayBindingBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>分散トランザクションとクラウドを介して、セキュリティで保護された信頼できるセッションをサポートする相互操作可能なバインディングを表します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントがクッキーを受け入れて、それらを今後の要求に反映させるかどうかを示す値を取得または設定します。 </summary>
        <value>返します<see cref="T:System.Boolean" />.true 場合は、バインディングにより、cookie です。 それ以外の場合は false。 既定値は false です。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wSHttpRelayBinding.CreateMessageSecurity " />
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
        <summary>現在のバインドからセキュリティ バインド要素を返します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />現在のバインドを格納しています。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransport">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement GetTransport ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement GetTransport() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBinding.GetTransport" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetTransport () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.GetTransport : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="wSHttpRelayBinding.GetTransport " />
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
        <summary>現在のバインドからトランスポート バインド要素を返します。 </summary>
        <returns>返します<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />です。現在のバインドからトランスポート バインド要素が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.WSHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.WSHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WSHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.WSHttpRelaySecurity" Usage="Microsoft.ServiceBus.WSHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.WSHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングで使用されるセキュリティ設定を取得します。 </summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.WSHttpRelaySecurity" />このバインディングで使用されるセキュリティを格納しています。 Mode プロパティの既定値は、メッセージです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>