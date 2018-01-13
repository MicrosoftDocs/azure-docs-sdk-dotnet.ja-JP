<Type Name="DataLakeAnalyticsCatalogManagementClient" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsCatalogManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsCatalogManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient&gt; implements class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsCatalogManagementClient&#xA;Inherits ServiceClient(Of DataLakeAnalyticsCatalogManagementClient)&#xA;Implements IAzureClient, IDataLakeAnalyticsCatalogManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsCatalogManagementClient = class&#xA;    inherit ServiceClient&lt;DataLakeAnalyticsCatalogManagementClient&gt;&#xA;    interface IDataLakeAnalyticsCatalogManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Data Lake Store filesystem 管理クライアントを作成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsCatalogManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            DataLakeAnalyticsCatalogManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsCatalogManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            DataLakeAnalyticsCatalogManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, string adlaCatalogDnsSuffix = &quot;azuredatalakeanalytics.net&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, string adlaCatalogDnsSuffix, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.String,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlaCatalogDnsSuffix As String = &quot;azuredatalakeanalytics.net&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient : Microsoft.Rest.ServiceClientCredentials * string * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient (credentials, userAgentAssemblyVersion, adlaCatalogDnsSuffix, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlaCatalogDnsSuffix" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Azure サブスクリプションの資格情報を取得します。
            </param>
        <param name="userAgentAssemblyVersion">
            省略可能。 すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。 既定では、SDK の現在のバージョンです。
            </param>
        <param name="adlaCatalogDnsSuffix">
            省略可能。 このクライアント インスタンスのすべての要求に使用する dns サフィックス。 既定値は、'azuredatalakeanalytics.net' です。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            DataLakeStoreFileSystemManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, string adlaCatalogDnsSuffix = &quot;azuredatalakeanalytics.net&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, string adlaCatalogDnsSuffix, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlaCatalogDnsSuffix As String = &quot;azuredatalakeanalytics.net&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient (credentials, rootHandler, userAgentAssemblyVersion, adlaCatalogDnsSuffix, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlaCatalogDnsSuffix" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Azure サブスクリプションの資格情報を取得します。
            </param>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="userAgentAssemblyVersion">
            省略可能。 すべての要求に対するユーザー エージェントのヘッダーで送信されるバージョン文字列です。 既定では、SDK の現在のバージョンです。
            </param>
        <param name="adlaCatalogDnsSuffix">
            省略可能。 このクライアント インスタンスのすべての要求に使用する dns サフィックス。 既定値は、'azuredatalakeanalytics.net' です。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            DataLakeStoreFileSystemManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答の優先言語を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdlaCatalogDnsSuffix">
      <MemberSignature Language="C#" Value="public string AdlaCatalogDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdlaCatalogDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.AdlaCatalogDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property AdlaCatalogDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.AdlaCatalogDnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.AdlaCatalogDnsSuffix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient.AdlaCatalogDnsSuffix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Data Lake Analytics Catalog のすべてのサービス要求のベースとして使用する DNS サフィックスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアント Api のバージョン。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Catalog">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations Catalog { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations Catalog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.Catalog" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Catalog As ICatalogOperations" />
      <MemberSignature Language="F#" Value="member this.Catalog : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.Catalog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ICatalogOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure に接続するクライアントに必要な資格情報です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json に逆シリアル化の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsCatalogManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。
            既定値は 30 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsCatalogManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json のシリアル化設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>