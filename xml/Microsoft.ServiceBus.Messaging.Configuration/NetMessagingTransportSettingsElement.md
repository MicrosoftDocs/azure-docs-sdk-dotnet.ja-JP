<Type Name="NetMessagingTransportSettingsElement" FullName="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportSettingsElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportSettingsElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportSettingsElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportSettingsElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="f1962-101">Net メッセージングのトランスポート設定要素を表します。</span><span class="sxs-lookup"><span data-stu-id="f1962-101">Represents the transport settings element for the net messaging.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportSettingsElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f1962-102"><see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f1962-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("batchFlushInterval", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f1962-103">取得またはバッチのフラッシュ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="f1962-103">Gets or sets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="f1962-104"><see cref="T:System.TimeSpan" />バッチのフラッシュ間隔を表すです。</span><span class="sxs-lookup"><span data-stu-id="f1962-104">The <see cref="T:System.TimeSpan" /> that represents the batch flush interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRedirect">
      <MemberSignature Language="C#" Value="public bool EnableRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.EnableRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.EnableRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("enableRedirect", IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f1962-105">取得または設定のリダイレクトが有効になっているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="f1962-105">Gets or set a value that indicates whether redirection is enabled.</span></span></summary>
        <value><span data-ttu-id="f1962-106">リダイレクトが有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f1962-106">true if redirection is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Configuration.NetMessagingTransportSettingsElement.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("leaseTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>