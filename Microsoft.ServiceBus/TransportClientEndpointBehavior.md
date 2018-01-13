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
    <summary>特定のエンドポイントに Service Bus の資格情報の指定に使用される WCF エンドポイントの動作について説明します。</summary>
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
        <summary><see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <param name="tokenProvider">バインド パラメーターとして使用されるトークン プロバイダー。</param>
        <summary><see cref="T:Microsoft.ServiceBus.TransportClientEndpointBehavior" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <param name="endpoint">変更するエンドポイント。</param>
        <param name="bindingParameters">動作をサポートするためにバインド要素が要求するオブジェクト。</param>
        <summary>
            この TransportClientEndpointBehavior を Bindingparameter コレクションに追加します。
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
        <param name="endpoint">カスタマイズ対象のエンドポイント。</param>
        <param name="clientRuntime">カスタマイズ対象のクライアント ランタイム。</param>
        <summary>
            この実装では、何も行われません。
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
        <param name="endpoint">カスタマイズ対象のエンドポイント。</param>
        <param name="endpointDispatcher">変更または拡張対象のエンドポイント ディスパッチャー。</param>
        <summary>
            この実装では、何も行われません。
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
        <param name="endpoint">エンドポイントにこの動作が適用されます。</param>
        <summary>
            このメソッドは何も実行しません。
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
        <summary>取得またはバインド パラメーターとして使用されるトークン プロバイダーを設定します。</summary>
        <value>バインド パラメーターとして使用されるトークン プロバイダー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>