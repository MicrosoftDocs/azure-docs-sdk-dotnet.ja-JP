<Type Name="ServiceBusEnvironment" FullName="Microsoft.ServiceBus.ServiceBusEnvironment">
  <TypeSignature Language="C#" Value="public static class ServiceBusEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceBusEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceBusEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusEnvironment" />
  <TypeSignature Language="F#" Value="type ServiceBusEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Service Bus 環境をについて説明します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAccessControlUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAccessControlUri (string serviceNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAccessControlUri(string serviceNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAccessControlUri (serviceNamespace As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAccessControlUri : string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateAccessControlUri serviceNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceNamespace">サービス名前空間の URI を作成します。</param>
        <summary>指定されたサービス名前空間のアクセス制御で使用する URI 文字列を作成します。</summary>
        <returns>返します、<see cref="T:System.Uri" />指定した URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheme">URI のスキーム。</param>
        <param name="serviceNamespace">アプリケーションで使用されるサービスの名前空間。</param>
        <param name="servicePath">URI のホスト名のセクションに依存しているサービスのパス。</param>
        <summary>指定されたスキーム、サービス名前空間、およびサービスのパスを使用して、アプリケーションのサービス バス URI を構築します。</summary>
        <returns>返します、<see cref="T:System.Uri" />新しい URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String, suppressRelayPathPrefix As Boolean) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string * bool -&gt; Uri" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath, suppressRelayPathPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
        <Parameter Name="suppressRelayPathPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scheme">URI のスキーム。</param>
        <param name="serviceNamespace">アプリケーションで使用されるサービスの名前空間。</param>
        <param name="servicePath">URI のホスト名のセクションに依存しているサービスのパス。</param>
        <param name="suppressRelayPathPrefix">True の場合、リレー パス プレフィックスが抑制されます。それ以外の場合は false です。</param>
        <summary>サービス バスの URI をアプリケーションでは、指定されたスキーム、サービス名前空間、およびサービスのパスを使用して、パス プレフィックスを中継を構築します。</summary>
        <returns>返します、<see cref="T:System.Uri" />新しい URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIdentityHostName">
      <MemberSignature Language="C#" Value="public static string DefaultIdentityHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultIdentityHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultIdentityHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultIdentityHostName : string" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>アクセス制御サービスの既定のホスト名を取得します。</summary>
        <value>既定の id のホスト名を返します。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.ConnectivitySettings SystemConnectivity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SystemConnectivity As ConnectivitySettings" />
      <MemberSignature Language="F#" Value="member this.SystemConnectivity : Microsoft.ServiceBus.ConnectivitySettings" Usage="Microsoft.ServiceBus.ServiceBusEnvironment.SystemConnectivity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivitySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>シングルトンを取得します<see cref="T:Microsoft.ServiceBus.ConnectivitySettings" />TCP や HTTP ベースのエンドポイントの接続設定を保持するインスタンス。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.ConnectivitySettings" />接続設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>