<Type Name="HttpsRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement">
  <TypeSignature Language="C#" Value="public class HttpsRelayTransportElement : Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpsRelayTransportElement extends Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpsRelayTransportElement&#xA;Inherits HttpRelayTransportElement" />
  <TypeSignature Language="F#" Value="type HttpsRelayTransportElement = class&#xA;    inherit HttpRelayTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.HttpRelayTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="faf69-101">Azure サービス バス経由で SOAP メッセージを送信するための HTTPS トランスポートを指定する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="faf69-101">Represents the configuration element that specifies an HTTPS transport for transmitting SOAP messages through the Azure Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpsRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="faf69-102"><see cref="T:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="faf69-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="faf69-103">バインド要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="faf69-103">Gets the type of the binding element.</span></span></summary>
        <value><span data-ttu-id="faf69-104">バインド要素の型。</span><span class="sxs-lookup"><span data-stu-id="faf69-104">The type of the binding element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpsRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="httpsRelayTransportElement.CreateDefaultBindingElement " />
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
        <summary><span data-ttu-id="faf69-105">この構成要素の設定からバインド要素を作成します。</span><span class="sxs-lookup"><span data-stu-id="faf69-105">Creates a binding element from settings in this configuration element.</span></span></summary>
        <returns><span data-ttu-id="faf69-106">返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />プロパティを持つは、この構成要素の設定からコピーされます。</span><span class="sxs-lookup"><span data-stu-id="faf69-106">Returns a <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> whose properties are copied from the settings in this configuration element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>