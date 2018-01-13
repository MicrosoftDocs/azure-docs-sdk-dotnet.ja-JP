<Type Name="DataLakeAnalyticsJobManagementClient" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsJobManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsJobManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient&gt; implements class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsJobManagementClient&#xA;Inherits ServiceClient(Of DataLakeAnalyticsJobManagementClient)&#xA;Implements IAzureClient, IDataLakeAnalyticsJobManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsJobManagementClient = class&#xA;    inherit ServiceClient&lt;DataLakeAnalyticsJobManagementClient&gt;&#xA;    interface IDataLakeAnalyticsJobManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient</InterfaceName>
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
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsJobManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient handlers" />
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
            DataLakeAnalyticsJobManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsJobManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient (rootHandler, handlers)" />
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
            DataLakeAnalyticsJobManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsJobManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, string adlaJobDnsSuffix = &quot;azuredatalakeanalytics.net&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, string adlaJobDnsSuffix, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.String,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlaJobDnsSuffix As String = &quot;azuredatalakeanalytics.net&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient : Microsoft.Rest.ServiceClientCredentials * string * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient (credentials, userAgentAssemblyVersion, adlaJobDnsSuffix, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlaJobDnsSuffix" Type="System.String" />
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
        <param name="adlaJobDnsSuffix">
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
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsJobManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, string adlaJobDnsSuffix = &quot;azuredatalakeanalytics.net&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, string adlaJobDnsSuffix, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlaJobDnsSuffix As String = &quot;azuredatalakeanalytics.net&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient (credentials, rootHandler, userAgentAssemblyVersion, adlaJobDnsSuffix, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlaJobDnsSuffix" Type="System.String" />
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
        <param name="adlaJobDnsSuffix">
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient.AcceptLanguage</InterfaceMember>
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
    <Member MemberName="AdlaJobDnsSuffix">
      <MemberSignature Language="C#" Value="public string AdlaJobDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdlaJobDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.AdlaJobDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property AdlaJobDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.AdlaJobDnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.AdlaJobDnsSuffix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient.AdlaJobDnsSuffix</InterfaceMember>
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
            Azure データ Lake Analytics ジョブのすべてのサービス要求のベースとして使用する DNS サフィックスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.ApiVersion" />
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
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Credentials" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.DeserializationSettings" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient.GenerateClientRequestId</InterfaceMember>
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
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IJobOperations Job { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations Job" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Job" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Job As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Job : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Job" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IJobOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsJobManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
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
    <Member MemberName="Pipeline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations Pipeline { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations Pipeline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Pipeline" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pipeline As IPipelineOperations" />
      <MemberSignature Language="F#" Value="member this.Pipeline : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Pipeline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IPipelineOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations Recurrence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recurrence As IRecurrenceOperations" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IRecurrenceOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsJobManagementClient.SerializationSettings" />
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