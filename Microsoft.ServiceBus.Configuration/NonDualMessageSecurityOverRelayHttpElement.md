<Type Name="NonDualMessageSecurityOverRelayHttpElement" FullName="Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement">
  <TypeSignature Language="C#" Value="public sealed class NonDualMessageSecurityOverRelayHttpElement : Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NonDualMessageSecurityOverRelayHttpElement extends Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NonDualMessageSecurityOverRelayHttpElement&#xA;Inherits MessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="F#" Value="type NonDualMessageSecurityOverRelayHttpElement = class&#xA;    inherit MessageSecurityOverRelayHttpElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>双方向サービス コントラクト以外の HTTP を使用して送信されるメッセージのセキュリティの構成設定を表します。 このクラスは継承できません。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NonDualMessageSecurityOverRelayHttpElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EstablishSecurityContext">
      <MemberSignature Language="C#" Value="public bool EstablishSecurityContext { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EstablishSecurityContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement.EstablishSecurityContext" />
      <MemberSignature Language="VB.NET" Value="Public Property EstablishSecurityContext As Boolean" />
      <MemberSignature Language="F#" Value="member this.EstablishSecurityContext : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement.EstablishSecurityContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("establishSecurityContext", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセキュリティ コンテキストが確立されたかどうかを定義する XML 値を設定します。</summary>
        <value>コンテキストが確立される場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>