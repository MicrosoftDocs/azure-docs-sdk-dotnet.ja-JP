<Type Name="ServiceRegistrySettingsElement" FullName="Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement">
  <TypeSignature Language="C#" Value="public class ServiceRegistrySettingsElement : System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRegistrySettingsElement extends System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRegistrySettingsElement&#xA;Inherits BehaviorExtensionElement" />
  <TypeSignature Language="F#" Value="type ServiceRegistrySettingsElement = class&#xA;    inherit BehaviorExtensionElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.BehaviorExtensionElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>AppFabric Service Bus レジストリの設定が含まれています。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettingsElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.#ctor" />
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
    <Member MemberName="BehaviorType">
      <MemberSignature Language="C#" Value="public override Type BehaviorType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BehaviorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.BehaviorType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BehaviorType As Type" />
      <MemberSignature Language="F#" Value="member this.BehaviorType : Type" Usage="Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.BehaviorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービスのレジストリ設定の動作の型を取得します。</summary>
        <value>サービスのレジストリ設定の動作の型。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBehavior">
      <MemberSignature Language="C#" Value="protected override object CreateBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object CreateBehavior() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.CreateBehavior" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateBehavior () As Object" />
      <MemberSignature Language="F#" Value="override this.CreateBehavior : unit -&gt; obj" Usage="serviceRegistrySettingsElement.CreateBehavior " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のレジストリ設定に基づく動作拡張を作成します。</summary>
        <returns>現在のレジストリ設定に基づく動作拡張。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiscoveryMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.DiscoveryType DiscoveryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.DiscoveryType DiscoveryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.DiscoveryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DiscoveryMode As DiscoveryType" />
      <MemberSignature Language="F#" Value="member this.DiscoveryMode : Microsoft.ServiceBus.DiscoveryType with get, set" Usage="Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.DiscoveryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("discoveryMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.DiscoveryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービスの検出方法を設定します。</summary>
        <value>検出の種類。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.Configuration.ServiceRegistrySettingsElement.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはエンドポイントの表示名を設定します。</summary>
        <value>表示名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>