<Type Name="WS2007HttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class WS2007HttpRelayBindingElement : Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WS2007HttpRelayBindingElement extends Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WS2007HttpRelayBindingElement&#xA;Inherits WSHttpRelayBindingElement" />
  <TypeSignature Language="F#" Value="type WS2007HttpRelayBindingElement = class&#xA;    inherit WSHttpRelayBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="58b4a-101">セキュリティ、ReliableSession、および transactionflow の各バインド要素の更新バージョンをサポートするバインディングの設定を格納する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="58b4a-101">Represents a configuration element that contains the settings for a binding that provides support for the updated versions of the Security, ReliableSession, and TransactionFlow binding elements.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="58b4a-102"><see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="58b4a-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WS2007HttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="58b4a-103">バインディングの名前。</span><span class="sxs-lookup"><span data-stu-id="58b4a-103">The name of the binding.</span></span> <span data-ttu-id="58b4a-104">この値は、バインディングの ID として使用されるため、一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="58b4a-104">This value should be unique because it is used as identification for the binding.</span></span></param>
        <summary><span data-ttu-id="58b4a-105">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" />指定の名前を使用します。</span><span class="sxs-lookup"><span data-stu-id="58b4a-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement" /> using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WS2007HttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="58b4a-106">現在のインスタンスのバインド要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="58b4a-106">Gets the type of the binding element of the current instance.</span></span></summary>
        <value><span data-ttu-id="58b4a-107">返します、<see cref="T:System.Type" />バインディング要素の型を格納しています。</span><span class="sxs-lookup"><span data-stu-id="58b4a-107">Returns a <see cref="T:System.Type" /> that contains the binding element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>