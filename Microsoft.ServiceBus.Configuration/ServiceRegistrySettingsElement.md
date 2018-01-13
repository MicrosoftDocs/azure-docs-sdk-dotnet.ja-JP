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
    <summary><span data-ttu-id="2a2b8-101">AppFabric Service Bus レジストリの設定が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-101">Contains the settings for the AppFabric Service Bus registry.</span></span></summary>
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
        <summary><span data-ttu-id="2a2b8-102">サービスのレジストリ設定の動作の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-102">Gets the behavior type for the service registry settings.</span></span></summary>
        <value><span data-ttu-id="2a2b8-103">サービスのレジストリ設定の動作の型。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-103">The behavior type for the service registry settings.</span></span></value>
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
        <summary><span data-ttu-id="2a2b8-104">現在のレジストリ設定に基づく動作拡張を作成します。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-104">Creates a behavior extension based on the current registry settings.</span></span></summary>
        <returns><span data-ttu-id="2a2b8-105">現在のレジストリ設定に基づく動作拡張。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-105">The behavior extension based on the current registry settings.</span></span></returns>
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
        <summary><span data-ttu-id="2a2b8-106">取得またはサービスの検出方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-106">Gets or sets how the service is discovered.</span></span></summary>
        <value><span data-ttu-id="2a2b8-107">検出の種類。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-107">The discovery type.</span></span></value>
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
        <summary><span data-ttu-id="2a2b8-108">取得またはエンドポイントの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-108">Gets or sets the display name for the endpoint.</span></span></summary>
        <value><span data-ttu-id="2a2b8-109">表示名。</span><span class="sxs-lookup"><span data-stu-id="2a2b8-109">The display name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>