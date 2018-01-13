<Type Name="ServiceBusConnectionStringBuilder" FullName="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type ServiceBusConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>作成および接続文字列の内容を管理する簡単な方法を提供します。 このクラスは、クライアントのメッセージング エンティティを作成するための接続文字列を構築するために使用できます。 既存の接続文字列で基本的な検証を実行するも使用できます。</summary>
    <remarks>To be added.</remarks>
    <code>
                次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。
                </code>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder : string -&gt; Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" Usage="new Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列、Azure 管理ポータルから取得できます。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder" />指定した既存の接続文字列を持つクラス。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException">接続文字列にエンドポイントがない場合にスローします。接続文字列には、トークン プロバイダーを作成するための十分な情報はありません。 たとえば、SasIssuer 名が SasIssuer キーではないを指定した場合に発生します。<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />値は有効ではありません<see cref="T:System.TimeSpan" />形式です。<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />または<see cref="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />値は整数形式ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingOAuthCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingOAuthCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingOAuthCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingOAuthCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingOAuthCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingOAuthCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints">エンドポイントのセット。</param>
        <param name="stsEndpoints">セキュリティ トークン サービス エンドポイントのセット。</param>
        <param name="runtimePort">ランタイム ポートです。</param>
        <param name="managementPort">管理ポートです。</param>
        <param name="domain">接続を確立するドメインです。</param>
        <param name="user">認証ユーザー。</param>
        <param name="password">認証のパスワード。</param>
        <summary>認証の資格情報を使用して接続文字列を作成します。</summary>
        <returns>作成したサービス バス接続文字列。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            エンドポイントまたはユーザーまたはパスワード
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (Uri endpoint, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Uri endpoint, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoint As Uri, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoint, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">エンドポイント。</param>
        <param name="keyName">共有アクセス キーの名前。</param>
        <param name="key">共有アクセス キー。</param>
        <summary>共有アクセス キーを使用して接続文字列を作成します。</summary>
        <returns>共有アクセス キーを使用して作成された接続。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedAccessKey">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedAccessKey (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, int runtimePort, int managementPort, string keyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedAccessKey(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, int32 runtimePort, int32 managementPort, string keyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey(System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedAccessKey (endpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, keyName As String, key As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedAccessKey : seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedAccessKey (endpoints, runtimePort, managementPort, keyName, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints">エンドポイントのセット。</param>
        <param name="runtimePort">ランタイム ポートです。</param>
        <param name="managementPort">管理ポートです。</param>
        <param name="keyName">共有アクセス キーの名前。</param>
        <param name="key">共有アクセス キー</param>
        <summary>共有アクセス キーを使用して接続文字列を作成します。</summary>
        <returns>共有アクセス キーを使用して作成された接続。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (Uri endpoint, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Uri endpoint, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoint As Uri, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : Uri * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoint, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">エンドポイント。</param>
        <param name="issuer">発行者</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>共有シークレット資格情報を使用して接続文字列を作成します。</summary>
        <returns>共有シークレット資格情報を使用して作成された接続。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            エンドポイントまたは発行者または issuerSecret
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingSharedSecret">
      <MemberSignature Language="C#" Value="public static string CreateUsingSharedSecret (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string issuer, string issuerSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingSharedSecret(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string issuer, string issuerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingSharedSecret (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, issuer As String, issuerSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingSharedSecret : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingSharedSecret (endpoints, stsEndpoints, runtimePort, managementPort, issuer, issuerSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="issuerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoints">エンドポイント。</param>
        <param name="stsEndpoints">セキュリティ トークン サービス エンドポイントのセット。</param>
        <param name="runtimePort">ランタイム ポートです。</param>
        <param name="managementPort">管理ポートです。</param>
        <param name="issuer">発行者。</param>
        <param name="issuerSecret">発行者のシークレット。</param>
        <summary>共有シークレット資格情報を使用して接続文字列を作成します。</summary>
        <returns>共有シークレット資格情報を使用して作成された接続。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            エンドポイントまたは発行者または issuerSecret
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateUsingWindowsCredential">
      <MemberSignature Language="C#" Value="public static string CreateUsingWindowsCredential (System.Collections.Generic.IEnumerable&lt;Uri&gt; endpoints, System.Collections.Generic.IEnumerable&lt;Uri&gt; stsEndpoints, int runtimePort, int managementPort, string domain, string user, System.Security.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string CreateUsingWindowsCredential(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; endpoints, class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; stsEndpoints, int32 runtimePort, int32 managementPort, string domain, string user, class System.Security.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential(System.Collections.Generic.IEnumerable{System.Uri},System.Collections.Generic.IEnumerable{System.Uri},System.Int32,System.Int32,System.String,System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUsingWindowsCredential (endpoints As IEnumerable(Of Uri), stsEndpoints As IEnumerable(Of Uri), runtimePort As Integer, managementPort As Integer, domain As String, user As String, password As SecureString) As String" />
      <MemberSignature Language="F#" Value="static member CreateUsingWindowsCredential : seq&lt;Uri&gt; * seq&lt;Uri&gt; * int * int * string * string * System.Security.SecureString -&gt; string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.CreateUsingWindowsCredential (endpoints, stsEndpoints, runtimePort, managementPort, domain, user, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="stsEndpoints" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="runtimePort" Type="System.Int32" />
        <Parameter Name="managementPort" Type="System.Int32" />
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="endpoints">一連のエンドポイント</param>
        <param name="stsEndpoints">セキュリティ トークン サービス エンドポイントのセット。</param>
        <param name="runtimePort">ランタイム ポートです。</param>
        <param name="managementPort">管理ポートです。</param>
        <param name="domain">接続を確立するドメインです。</param>
        <param name="user">ユーザー。</param>
        <param name="password">Windows のパスワード。</param>
        <summary>Windows 資格情報を使用して接続文字列を作成します。</summary>
        <returns>作成された接続文字列。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            エンドポイントまたはユーザーまたはパスワード
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービス エンドポイントのコレクションを取得します。 各エンドポイントは、同じ Service Bus 名前空間を参照する必要があります。</summary>
        <value>エンドポイントのセット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteManagementEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteManagementEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteManagementEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteManagementEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteManagementEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteManagementEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>絶対管理エンドポイントを取得します。</summary>
        <returns>絶対管理エンドポイント</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAbsoluteRuntimeEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Uri&gt; GetAbsoluteRuntimeEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IList`1&lt;class System.Uri&gt; GetAbsoluteRuntimeEndpoints() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAbsoluteRuntimeEndpoints () As IList(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAbsoluteRuntimeEndpoints : unit -&gt; System.Collections.Generic.IList&lt;Uri&gt;" Usage="serviceBusConnectionStringBuilder.GetAbsoluteRuntimeEndpoints " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>絶対ランタイム エンドポイントを取得します。</summary>
        <returns>絶対ランタイムのエンドポイント。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementPort">
      <MemberSignature Language="C#" Value="public int ManagementPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ManagementPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ManagementPort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ManagementPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または管理操作用の TCP ポート番号を設定します。</summary>
        <value>管理ポートです。</value>
        <remarks>これは、サーバーのシナリオでのみ使用します。 Azure サービスへの接続文字列を生成するときにこれを既定値です。 残してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthDomain">
      <MemberSignature Language="C#" Value="public string OAuthDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthDomain As String" />
      <MemberSignature Language="F#" Value="member this.OAuthDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または認証のドメインの接続を設定します。</summary>
        <value>接続の認証のドメイン。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString OAuthPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString OAuthPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.OAuthPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または接続の認証のパスワードを設定します。</summary>
        <value>接続の認証のパスワード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuthUsername">
      <MemberSignature Language="C#" Value="public string OAuthUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OAuthUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property OAuthUsername As String" />
      <MemberSignature Language="F#" Value="member this.OAuthUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OAuthUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または接続の認証ユーザー名を設定します。</summary>
        <value>接続の認証ユーザー名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</summary>
        <value><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。既定値は、1 分です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimePort">
      <MemberSignature Language="C#" Value="public int RuntimePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RuntimePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimePort As Integer" />
      <MemberSignature Language="F#" Value="member this.RuntimePort : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.RuntimePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはランタイム操作用の TCP ポート番号を設定します。</summary>
        <value>ランタイム ポートです。</value>
        <remarks>これは、サーバーのシナリオでのみ使用します。 Azure サービスへの接続文字列を生成するときにこれを既定値です。 残してください。</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または接続の認証用の共有アクセス キーを設定します。</summary>
        <value>接続の認証用の共有アクセス キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有アクセス キーの名前を設定します。</summary>
        <value>共有アクセス キーの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerName">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerName As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有シークレットの発行者名を設定します。</summary>
        <value>共有シークレットの発行者の名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecretIssuerSecret">
      <MemberSignature Language="C#" Value="public string SharedSecretIssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedSecretIssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedSecretIssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.SharedSecretIssuerSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.SharedSecretIssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または共有シークレットの発行者のシークレットを設定します。</summary>
        <value>共有シークレットの発行者のシークレット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StsEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;Uri&gt; StsEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;class System.Uri&gt; StsEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StsEndpoints As HashSet(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.StsEndpoints : System.Collections.Generic.HashSet&lt;Uri&gt;" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.StsEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>STS エンドポイントのセットを取得します。</summary>
        <value>STS エンドポイントのセット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceBusConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>現在のオブジェクトを表す文字列を返します。</summary>
        <returns>現在のオブジェクトを表す文字列。</returns>
        <remarks>To be added.</remarks>
        <code>
                次のサンプル コードには、既存//接続文字列を Amqp を使用するトランスポートの種類の変更は、//フォーム var ビルダーの文字列で、新しい接続文字列を返す新しい ServiceBusConnectionStringBuilder(connectionString); を =ビルダー。TransportType TransportType.Amqp; を =Console.WriteLine (ビルダー。ToString()) です。
                </code>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialDomain">
      <MemberSignature Language="C#" Value="public string WindowsCredentialDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialDomain As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialDomain : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Windows 資格情報のドメインを設定します。</summary>
        <value>Windows では、ドメイン資格情報します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialPassword">
      <MemberSignature Language="C#" Value="public System.Security.SecureString WindowsCredentialPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString WindowsCredentialPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialPassword : System.Security.SecureString with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Windows 資格情報のパスワードを設定します。</summary>
        <value>Windows 資格情報のパスワード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsCredentialUsername">
      <MemberSignature Language="C#" Value="public string WindowsCredentialUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsCredentialUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsCredentialUsername As String" />
      <MemberSignature Language="F#" Value="member this.WindowsCredentialUsername : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusConnectionStringBuilder.WindowsCredentialUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Windows 資格情報のユーザー名を設定します。</summary>
        <value>Windows 資格情報のユーザー名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>