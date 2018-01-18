<Type Name="HttpsRelayTransportBindingElement" FullName="Microsoft.ServiceBus.HttpsRelayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class HttpsRelayTransportBindingElement : Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpsRelayTransportBindingElement extends Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpsRelayTransportBindingElement&#xA;Inherits HttpRelayTransportBindingElement" />
  <TypeSignature Language="F#" Value="type HttpsRelayTransportBindingElement = class&#xA;    inherit HttpRelayTransportBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.HttpRelayTransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1c1d5-101">メッセージ送信用の HTTPS リレー トランスポートを指定するために使用するバインド要素を表します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-101">Represents the binding element used to specify an HTTPS relay transport for transmitting messages.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpsRelayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c1d5-102">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、既定の設定を使用します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" /> class, using the default settings.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HttpsRelayTransportBindingElement (Microsoft.ServiceBus.HttpsRelayTransportBindingElement elementToBeCloned);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.HttpsRelayTransportBindingElement elementToBeCloned) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.HttpsRelayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (elementToBeCloned As HttpsRelayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpsRelayTransportBindingElement : Microsoft.ServiceBus.HttpsRelayTransportBindingElement -&gt; Microsoft.ServiceBus.HttpsRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpsRelayTransportBindingElement elementToBeCloned" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToBeCloned" Type="Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToBeCloned"><span data-ttu-id="1c1d5-103">複製対象となる要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-103">The element to be cloned.</span></span></param>
        <summary><span data-ttu-id="1c1d5-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、指定した要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" /> class, using the specified element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpsRelayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpsRelayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.HttpsRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpsRelayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType"><span data-ttu-id="1c1d5-105">リレー クライアントの認証の種類。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-105">The relay client authentication type.</span></span></param>
        <summary><span data-ttu-id="1c1d5-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、指定した型のクライアント認証を使用します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" /> class, using the specified type of client authentication.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="httpsRelayTransportBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c1d5-107">現在のバインド要素のディープ コピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-107">Creates a deep copy of the current binding element.</span></span></summary>
        <returns><span data-ttu-id="1c1d5-108">現在のバインド要素のディープ コピーです。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-108">A deep copy of the current binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.CreateInnerChannelBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateInnerChannelBindingElement () As HttpTransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateInnerChannelBindingElement : unit -&gt; System.ServiceModel.Channels.HttpTransportBindingElement" Usage="httpsRelayTransportBindingElement.CreateInnerChannelBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.HttpTransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1c1d5-109">作成、<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルのバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-109">Creates a <see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" /> binding element for the inner channel.</span></span></summary>
        <returns><span data-ttu-id="1c1d5-110">内部チャネルのバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-110">A binding element for the inner channel.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="httpsRelayTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="1c1d5-111">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-111">The binding context.</span></span></param>
        <summary><span data-ttu-id="1c1d5-112">指定したバインド コンテキストから指定したプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-112">Gets the specified property from the specified binding context.</span></span></summary>
        <returns><span data-ttu-id="1c1d5-113">プロパティが含まれているバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-113">A binding element that contains the property.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected override void InitializeInnerChannelBindingElement (System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeInnerChannelBindingElement(class System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.InitializeInnerChannelBindingElement(System.ServiceModel.Channels.HttpTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub InitializeInnerChannelBindingElement (httpTransportElement As HttpTransportBindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeInnerChannelBindingElement : System.ServiceModel.Channels.HttpTransportBindingElement -&gt; unit" Usage="httpsRelayTransportBindingElement.InitializeInnerChannelBindingElement httpTransportElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpTransportElement" Type="System.ServiceModel.Channels.HttpTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="httpTransportElement"> <span data-ttu-id="1c1d5-114">初期化するためにバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-114">The binding element to initialize.</span></span></param>
        <summary><span data-ttu-id="1c1d5-115">現在のインスタンスの設定で指定されたバインド要素の初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />バインド要素。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-115">Initializes the specified binding element with the settings from the current instance of the<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" /> binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpsRelayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.HttpsRelayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1c1d5-116">トランスポートの URI スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-116">Gets the URI scheme for the transport.</span></span></summary>
        <value><span data-ttu-id="1c1d5-117">"HTTPS"であるトランスポートの URI スキーム。</span><span class="sxs-lookup"><span data-stu-id="1c1d5-117">The URI scheme for the transport, which is “HTTPS”.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>