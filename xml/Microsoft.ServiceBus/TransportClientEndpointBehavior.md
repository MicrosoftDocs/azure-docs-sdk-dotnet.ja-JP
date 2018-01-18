<Type Name="TransportClientEndpointBehavior" FullName="Microsoft.ServiceBus.TransportClientEndpointBehavior">
  <TypeSignature Language="C#" Value="public sealed class TransportClientEndpointBehavior : System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TransportClientEndpointBehavior extends System.Object implements class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TransportClientEndpointBehavior&#xA;Implements IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type TransportClientEndpointBehavior = class&#xA;    interface IEndpointBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IEndpointBehavior</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="6f3ff-101">特定のエンドポイントに Service Bus の資格情報の指定に使用される WCF エンドポイントの動作について説明します。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-101">Describes the WCF endpoint behavior that is used to specify the Service Bus credentials for a particular endpoint.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehavior ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6f3ff-102"><see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransportClientEndpointBehavior (Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.#ctor(Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TransportClientEndpointBehavior : Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.TransportClientEndpointBehavior" Usage="new Microsoft.ServiceBus.TransportClientEndpointBehavior tokenProvider" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="tokenProvider"><span data-ttu-id="6f3ff-103">バインド パラメーターとして使用されるトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-103">The token provider used as a binding parameter.</span></span></param>
        <summary><span data-ttu-id="6f3ff-104"><see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
      <MemberSignature Language="VB.NET" Value="Sub AddBindingParameters (endpoint As ServiceEndpoint, bindingParameters As BindingParameterCollection) Implements IEndpointBehavior.AddBindingParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="bindingParameters" Type="System.ServiceModel.Channels.BindingParameterCollection" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="6f3ff-105">変更するエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-105">The endpoint to modify.</span></span></param>
        <param name="bindingParameters"><span data-ttu-id="6f3ff-106">動作をサポートするためにバインド要素が要求するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-106">The objects that binding elements require to support the behavior.</span></span></param>
        <summary>
            <span data-ttu-id="6f3ff-107">この TransportClientEndpointBehavior を Bindingparameter コレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-107">Adds this TransportClientEndpointBehavior to the bindingParameters collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="clientRuntime" Type="System.ServiceModel.Dispatcher.ClientRuntime" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="6f3ff-108">カスタマイズ対象のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-108">The endpoint that is to be customized.</span></span></param>
        <param name="clientRuntime"><span data-ttu-id="6f3ff-109">カスタマイズ対象のクライアント ランタイム。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-109">The client runtime to be customized.</span></span></param>
        <summary>
            <span data-ttu-id="6f3ff-110">この実装では、何も行われません。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-110">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyDispatchBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.EndpointDispatcher endpointDispatcher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
        <Parameter Name="endpointDispatcher" Type="System.ServiceModel.Dispatcher.EndpointDispatcher" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="6f3ff-111">カスタマイズ対象のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-111">The endpoint that is to be customized.</span></span></param>
        <param name="endpointDispatcher"><span data-ttu-id="6f3ff-112">変更または拡張対象のエンドポイント ディスパッチャー。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-112">The endpoint dispatcher to be modified or extended.</span></span></param>
        <summary>
            <span data-ttu-id="6f3ff-113">この実装では、何も行われません。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-113">This implementation does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.Validate">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.Validate (System.ServiceModel.Description.ServiceEndpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.Validate(class System.ServiceModel.Description.ServiceEndpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TransportClientEndpointBehavior.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
      <MemberSignature Language="VB.NET" Value="Sub Validate (endpoint As ServiceEndpoint) Implements IEndpointBehavior.Validate" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IEndpointBehavior.Validate(System.ServiceModel.Description.ServiceEndpoint)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.ServiceModel.Description.ServiceEndpoint" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="6f3ff-114">エンドポイントにこの動作が適用されます。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-114">The endpoint this behavior applies to.</span></span></param>
        <summary>
            <span data-ttu-id="6f3ff-115">このメソッドは何も実行しません。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-115">This method does nothing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TransportClientEndpointBehavior.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.TokenProvider with get, set" Usage="Microsoft.ServiceBus.TransportClientEndpointBehavior.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6f3ff-116">取得またはバインド パラメーターとして使用されるトークン プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-116">Gets or sets the token provider that is used as a binding parameter.</span></span></summary>
        <value><span data-ttu-id="6f3ff-117">バインド パラメーターとして使用されるトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="6f3ff-117">The token provider used as a binding parameter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>