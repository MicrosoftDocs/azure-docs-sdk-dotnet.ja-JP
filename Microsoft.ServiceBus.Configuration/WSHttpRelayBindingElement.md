<Type Name="WSHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingElement : Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingElement extends Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingElement&#xA;Inherits WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingElement = class&#xA;    inherit WSHttpRelayBindingBaseElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>分散トランザクションとセキュリティで保護された信頼できるセッションをサポートする相互操作可能なバインドを表す構成要素。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("allowCookies", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはをサービスまたはクライアントが cookie を受け入れ、それらを今後の要求に反映させるかどうかを示す値を設定します。</summary>
        <value>サービスまたはクライアント クッキーを受け入れて、それらを今後の要求に反映させる場合は true。それ以外の場合は false です。 既定値は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>型を取得、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</summary>
        <value>型、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> この構成要素を初期化するためにバインドします。</param>
        <summary>このバインディング構成要素を指定したバインディングの内容で初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> 設定を更新するバインディング。</param>
        <summary>指定されたバインディングには、この構成要素の設定を適用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディング構成要素のプロパティのコレクションを取得します。</summary>
        <value>このバインディング構成要素のプロパティのコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WSHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />のセキュリティ設定を格納する構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />のセキュリティ設定を格納する構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>