<Type Name="ServiceRegistrySettings" FullName="Microsoft.ServiceBus.ServiceRegistrySettings">
  <TypeSignature Language="C#" Value="public class ServiceRegistrySettings : System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRegistrySettings extends System.Object implements class System.ServiceModel.Description.IEndpointBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceRegistrySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRegistrySettings&#xA;Implements IEndpointBehavior" />
  <TypeSignature Language="F#" Value="type ServiceRegistrySettings = class&#xA;    interface IEndpointBehavior" />
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
    <summary>Azure Service Bus レジストリの設定が含まれています。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRegistrySettings (Microsoft.ServiceBus.DiscoveryType discoveryType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.DiscoveryType discoveryType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.#ctor(Microsoft.ServiceBus.DiscoveryType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.ServiceRegistrySettings : Microsoft.ServiceBus.DiscoveryType -&gt; Microsoft.ServiceBus.ServiceRegistrySettings" Usage="new Microsoft.ServiceBus.ServiceRegistrySettings discoveryType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="discoveryType" Type="Microsoft.ServiceBus.DiscoveryType" />
      </Parameters>
      <Docs>
        <param name="discoveryType">エンドポイントがパブリックかプライベートかどうかを示す検出の種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.ServiceRegistrySettings" />クラスの指定された探索の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="allowUnauthenticatedAccess">
      <MemberSignature Language="C#" Value="protected bool allowUnauthenticatedAccess;" />
      <MemberSignature Language="ILAsm" Value=".field family bool allowUnauthenticatedAccess" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberSignature Language="VB.NET" Value="Protected allowUnauthenticatedAccess As Boolean " />
      <MemberSignature Language="F#" Value="val mutable allowUnauthenticatedAccess : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.allowUnauthenticatedAccess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>エンドポイントにより、認証されていないアクセス以外の場合は true。それ以外の場合は false です。 既定値は false です。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiscoveryMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.DiscoveryType DiscoveryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.DiscoveryType DiscoveryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DiscoveryMode As DiscoveryType" />
      <MemberSignature Language="F#" Value="member this.DiscoveryMode : Microsoft.ServiceBus.DiscoveryType with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DiscoveryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.DiscoveryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービスの検出方法を設定します。 </summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.DiscoveryType" />です。パブリック; にするための探索の DiscoveryType.Publicプライベートにするための探索の DiscoveryType.Private します。 既定値は、DiscoveryType.Private です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはエンドポイントの表示名を設定します。</summary>
        <value>返します<see cref="T:System.String" />です。表示名が含まれています。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.AddBindingParameters (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Channels.BindingParameterCollection bindingParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.AddBindingParameters(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Channels.BindingParameterCollection bindingParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#AddBindingParameters(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Channels.BindingParameterCollection)" />
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
            実行時に、カスタム動作をサポートするバインディングにデータを渡します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior">
      <MemberSignature Language="C#" Value="void IEndpointBehavior.ApplyClientBehavior (System.ServiceModel.Description.ServiceEndpoint endpoint, System.ServiceModel.Dispatcher.ClientRuntime clientRuntime);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IEndpointBehavior.ApplyClientBehavior(class System.ServiceModel.Description.ServiceEndpoint endpoint, class System.ServiceModel.Dispatcher.ClientRuntime clientRuntime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyClientBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.ClientRuntime)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#ApplyDispatchBehavior(System.ServiceModel.Description.ServiceEndpoint,System.ServiceModel.Dispatcher.EndpointDispatcher)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceRegistrySettings.System#ServiceModel#Description#IEndpointBehavior#Validate(System.ServiceModel.Description.ServiceEndpoint)" />
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
    <Member MemberName="transportProtectionEnabled">
      <MemberSignature Language="C#" Value="protected bool transportProtectionEnabled;" />
      <MemberSignature Language="ILAsm" Value=".field family bool transportProtectionEnabled" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected transportProtectionEnabled As Boolean " />
      <MemberSignature Language="F#" Value="val mutable transportProtectionEnabled : bool" Usage="Microsoft.ServiceBus.ServiceRegistrySettings.transportProtectionEnabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トランスポートの保護が有効である場合は true。それ以外の場合は false です。 既定値は true です。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>