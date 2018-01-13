<Type Name="ServiceBusEnvironment" FullName="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment">
  <TypeSignature Language="C#" Value="public static class ServiceBusEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceBusEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusEnvironment" />
  <TypeSignature Language="F#" Value="type ServiceBusEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Windows Azure Service Bus 環境をについて説明します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAccessControlUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAccessControlUri (string serviceNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAccessControlUri(string serviceNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateAccessControlUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAccessControlUri (serviceNamespace As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAccessControlUri : string -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateAccessControlUri serviceNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceNamespace">URI を作成します。</param>
        <summary>指定されたアクセス制御で使用する URI 文字列を作成します。</summary>
        <returns>返します、<see cref="T:System.Uri" />指定した URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="serviceNamespace">アプリケーションで使用される名前です。</param>
        <param name="servicePath">URI のホスト名のセクションに依存しているサービスのパス。</param>
        <summary>Windows Azure サービス バスの URI、アプリケーションでは、指定されたスキーム、名、およびサービスのパスを使用してを構築します。</summary>
        <returns>返します、<see cref="T:System.Uri" />新しい URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String, suppressRelayPathPrefix As Boolean) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string * bool -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath, suppressRelayPathPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="serviceNamespace">アプリケーションで使用される名前です。</param>
        <param name="servicePath">URI のホスト名のセクションに依存しているサービスのパス。</param>
        <param name="suppressRelayPathPrefix">True の場合、リレー パス プレフィックスが抑制されます。それ以外の場合は false です。</param>
        <summary>Windows Azure サービス バスの URI、アプリケーションでは、指定されたスキーム、名前、およびサービスのパスを使用して、パス プレフィックスをリレー型を構築します。</summary>
        <returns>返します、<see cref="T:System.Uri" />新しい URI を格納しています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIdentityHostName">
      <MemberSignature Language="C#" Value="public static string DefaultIdentityHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultIdentityHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultIdentityHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultIdentityHostName : string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Windows Azure アクセス制御サービスの既定のホスト名を取得します。</summary>
        <value>既定の id のホスト名を返します。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.ConnectivitySettings SystemConnectivity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.NotificationHubs.ConnectivitySettings SystemConnectivity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.SystemConnectivity" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SystemConnectivity As ConnectivitySettings" />
      <MemberSignature Language="F#" Value="member this.SystemConnectivity : Microsoft.Azure.NotificationHubs.ConnectivitySettings" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.SystemConnectivity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivitySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>シングルトンを取得します<see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" />TCP や HTTP ベースのエンドポイントの接続設定を保持するインスタンス。</summary>
        <value>返します、<see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" />接続設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>