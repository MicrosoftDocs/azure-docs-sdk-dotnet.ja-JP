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
    <summary>メッセージ送信用の HTTPS リレー トランスポートを指定するために使用するバインド要素を表します。</summary>
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
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、既定の設定を使用します。</summary>
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
        <param name="elementToBeCloned">複製対象となる要素。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、指定した要素を使用します。</summary>
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
        <param name="relayClientAuthenticationType">リレー クライアントの認証の種類。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />クラス、指定した型のクライアント認証を使用します。</summary>
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
        <summary>現在のバインド要素のディープ コピーを作成します。</summary>
        <returns>現在のバインド要素のディープ コピーです。</returns>
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
        <summary>作成、<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルのバインド要素。</summary>
        <returns>内部チャネルのバインド要素。</returns>
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
        <param name="context"> バインド コンテキスト。</param>
        <summary>指定したバインド コンテキストから指定したプロパティを取得します。</summary>
        <returns>プロパティが含まれているバインド要素。</returns>
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
        <param name="httpTransportElement"> 初期化するためにバインド要素。</param>
        <summary>現在のインスタンスの設定で指定されたバインド要素の初期化、<see cref="T:Microsoft.ServiceBus.HttpsRelayTransportBindingElement" />バインド要素。</summary>
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
        <summary>トランスポートの URI スキームを取得します。</summary>
        <value>"HTTPS"であるトランスポートの URI スキーム。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>