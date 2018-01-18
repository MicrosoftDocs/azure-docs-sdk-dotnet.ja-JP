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
    <summary><span data-ttu-id="386a6-101">分散トランザクションとセキュリティで保護された信頼できるセッションをサポートする相互操作可能なバインドを表す構成要素。</span><span class="sxs-lookup"><span data-stu-id="386a6-101">A configuration element that represents an interoperable binding that supports distributed transactions and secure, reliable sessions.</span></span></summary>
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
        <summary><span data-ttu-id="386a6-102">取得またはをサービスまたはクライアントが cookie を受け入れ、それらを今後の要求に反映させるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="386a6-102">Gets or sets a value that indicates whether the service or client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="386a6-103">サービスまたはクライアント クッキーを受け入れて、それらを今後の要求に反映させる場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="386a6-103">true if the service or client accepts cookies and propagates them on future requests; otherwise, false.</span></span> <span data-ttu-id="386a6-104">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="386a6-104">The default is false.</span></span></value>
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
        <summary><span data-ttu-id="386a6-105">型を取得、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="386a6-105">Gets the type of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="386a6-106">型、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="386a6-106">The type of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
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
        <param name="binding"> <span data-ttu-id="386a6-107">この構成要素を初期化するためにバインドします。</span><span class="sxs-lookup"><span data-stu-id="386a6-107">The binding to initialize this configuration element from.</span></span></param>
        <summary><span data-ttu-id="386a6-108">このバインディング構成要素を指定したバインディングの内容で初期化します。</span><span class="sxs-lookup"><span data-stu-id="386a6-108">Initializes this binding configuration element with the content of the specfied binding.</span></span></summary>
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
        <param name="binding"> <span data-ttu-id="386a6-109">設定を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="386a6-109">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="386a6-110">指定されたバインディングには、この構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="386a6-110">Applies the settings of this configuration element to the specified binding.</span></span></summary>
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
        <summary><span data-ttu-id="386a6-111">このバインディング構成要素のプロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="386a6-111">Gets a collection of properties of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="386a6-112">このバインディング構成要素のプロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="386a6-112">A collection of properties of this binding configuration element.</span></span></value>
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
        <summary><span data-ttu-id="386a6-113">取得、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />のセキュリティ設定を格納する構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="386a6-113">Gets the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> configuration element that contains the security settings for the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="386a6-114"><see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />のセキュリティ設定を格納する構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="386a6-114">The <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> configuration element that contains the security settings for the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>