<Type Name="TransportClientEndpointBehaviorElement" FullName="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement">
  <TypeSignature Language="C#" Value="public class TransportClientEndpointBehaviorElement : System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransportClientEndpointBehaviorElement extends System.ServiceModel.Configuration.BehaviorExtensionElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TransportClientEndpointBehaviorElement&#xA;Inherits BehaviorExtensionElement" />
  <TypeSignature Language="F#" Value="type TransportClientEndpointBehaviorElement = class&#xA;    inherit BehaviorExtensionElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.BehaviorExtensionElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="19e75-101">Azure Service Bus リレーのトランスポートのサービスまたはクライアント エンドポイントの動作を指定する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="19e75-101">Represents a configuration element that specifies the behavior of a service or client endpoint for a transport on the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehaviorElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.#ctor" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BehaviorType As Type" />
      <MemberSignature Language="F#" Value="member this.BehaviorType : Type" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.BehaviorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="19e75-102">取得またはトランスポート クライアント エンドポイントの動作の型を設定します。</span><span class="sxs-lookup"><span data-stu-id="19e75-102">Gets or sets the behavior type for the transport client endpoint.</span></span></summary>
        <value><span data-ttu-id="19e75-103">トランスポート クライアント エンドポイントの動作の型。</span><span class="sxs-lookup"><span data-stu-id="19e75-103">The behavior type for the transport client endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="transportClientEndpointBehaviorElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> <span data-ttu-id="19e75-104">コンテンツをコピーする構成要素。</span><span class="sxs-lookup"><span data-stu-id="19e75-104">The configuration element to copy the contents from.</span></span></param>
        <summary><span data-ttu-id="19e75-105">この構成要素に指定された構成要素の内容をコピーします。</span><span class="sxs-lookup"><span data-stu-id="19e75-105">Copies the contents of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBehavior">
      <MemberSignature Language="C#" Value="protected override object CreateBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object CreateBehavior() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.CreateBehavior" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateBehavior () As Object" />
      <MemberSignature Language="F#" Value="override this.CreateBehavior : unit -&gt; obj" Usage="transportClientEndpointBehaviorElement.CreateBehavior " />
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
        <summary><span data-ttu-id="19e75-106">新しいを返します<see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" />この構成要素と同じ設定を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="19e75-106">Returns a new <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> object with the same settings as this configuration element.</span></span></summary>
        <returns><span data-ttu-id="19e75-107">新しい<see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" />この構成要素と同じ設定を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="19e75-107">A new <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> object with the same settings as this configuration element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="19e75-108">この構成要素に含まれるプロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="19e75-108">Gets the collection of properties contained in this configuration element.</span></span></summary>
        <value><span data-ttu-id="19e75-109">この構成要素に含まれるプロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="19e75-109">The collection of properties contained in this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.TokenProviderElement TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.TokenProviderElement TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProviderElement" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.Configuration.TokenProviderElement" Usage="Microsoft.ServiceBus.Configuration.TransportClientEndpointBehaviorElement.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenProvider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.TokenProviderElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="19e75-110">取得またはバインド パラメーターとして使用されるトークン プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="19e75-110">Gets or sets the token provider that is used as a binding parameter.</span></span></summary>
        <value><span data-ttu-id="19e75-111">バインド パラメーターとして使用されるトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="19e75-111">The token provider used as a binding parameter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>